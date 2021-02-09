# Read: 06a - Functions

# FUNCTION
 Function is part of script and it is a series of statements together to perform a specific task, if we use a block of code many times, we could convert this block of code into a function. we define the code once in our script, and we just call the function in one line if we need to use it.

```javaScript
var msg = 'Sign up to receive our newsletter for 10% off!';

function updateMessage() {
var el = document.getElementByld('message');
el .textContent = msg;
}

updateMessage();

```

## Declare a function does not need information

```javaScript
Function sayHello( ){
document.write(“Hello”);
}
```

## Calling a function does not need information
` sayHello( );`

## Declare a function need information

```javaScript
Function getArea(width, hight){
return width * hight;
}
```

## Calling a function need information
`getArea(width, hight);` or we can assign the return value to variable `var area = getArea(width, hight)`
