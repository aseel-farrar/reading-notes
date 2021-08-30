# Read: 42 - Location

- Using the Google Play services location APIs, your app can request the last known location of the user's device.

## Set up Google Play services

- To access the fused location provider, your app's development project must include Google Play services.
- Download and install the Google Play services component via the SDK Manager and add the library to your project.

## Specify app permissions

- Apps whose features use location services must request location permissions, depending on the use cases of those features.

## Create location services client

- In your activity's onCreate() method, create an instance of the Fused Location Provider Client

## Get the last known location

- Once you have created the Location Services client you can get the last known location of a user's device. When your app is connected to these you can use the fused location provider's getLastLocation() method to retrieve the device location.

## Get the last known location

### Create location services client

- In your activity's `onCreate()` method, create an instance of the Fused Location Provider Client as the following code snippet shows.

```java
private FusedLocationProviderClient fusedLocationClient;

// ..

@Override
protected void onCreate(Bundle savedInstanceState) {
    // ...

    fusedLocationClient = LocationServices.getFusedLocationProviderClient(this);
}
```

- To request the last known location, call the `getLastLocation()` method. The following code snippet illustrates the request and a simple handling of the response:

```java
fusedLocationClient.getLastLocation()
        .addOnSuccessListener(this, new OnSuccessListener<Location>() {
            @Override
            public void onSuccess(Location location) {
                // Got last known location. In some rare situations this can be null.
                if (location != null) {
                    // Logic to handle location object
                }
            }
        });

```

### Location Permission

You need to add these permissions to your manifest file:

```xml
<manifest ... >
  <!-- To request foreground location access, declare one of these permissions. -->
  <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
  <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
</manifest>

```
