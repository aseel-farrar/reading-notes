# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions

## Headings
HTML has six "levels" of headings:

```html
<h1>This is a Main Heading</h1>
<h2>This is a Level 2 Heading</h2>
<h3>This is a Level 3 Heading</h3>
<h4>This is a Level 4 Heading</h4>
<h5>This is a Level 5 Heading</h5>
<h6>This is a Level 6 Heading</h6>
```
## Paragraphs
To create a paragraph, surround the words that make up the paragraph with an opening `<p>` tag and closing `</p>` tag.
```html
<p>A paragraph consists of one or more sentences that form a self-contained unit of discourse. The start of a paragraph is indicated by a new line.</p> 
```
## Bold & iTalic
By enclosing words in the tags` <b>` and `</b>` we can make characters appear bold.
`<p>This is how we make a word appear <b>bold.</b></p>`
By enclosing words in the tags <i> and </i> we can make characters appear italic.
`p>This is how we make a word appear <i>italic</i>.</p> `

## Strong & Emphasis
The use of the` <strong>` element indicates that its content has strong importance.
```html
<p><strong>Beware:</strong> Pickpockets operate in this area.</p>
<p>This toy has many small pieces and is <strong>not suitable for children under five years old. </strong></p>
```
The `<em>` element indicates emphasis that subtly changes the meaning of a sentence.
```html
<p>I <em>think</em> Ivy was the first.</p>
<p>I think <em>Ivy</em> was the first.</p>
<p>I think Ivy was the <em>first</em>.</p>
```

## Superscript & Subscript
The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.
The `<sub>` element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H 20.
```html
<p>On the 4<sup>th</sup> of September you will learn about E=MC<sup>2</sup>.</p>
<p>The amount of CO<sub>2</sub> in the atmosphere grew by 2ppm in 2009<sub>1</sub>.</p>
```
line Breaks & Horizontal rules
To add a line break inside use `<br/>`
To create horizontal line use `<hr/>`
```html
<p>The Earth<br />gets one hundred tons heavier every day<br />due to falling space dust.</p>
<p>Venus is the only planet that rotates clockwise.</p>
<hr />
<p>Jupiter is bigger than all the other planets combined.</p>
```

## Quotations
There are two elements commonly used for marking up quotations: 
1.  The `<blockquote>` element is used for longer quotes that take up an entire paragraph. 
2.  The `<q>` element is used for shorter quotes that sit within a paragraph.
```html
<blockquote cite="http://en.wikipedia.org/wiki/ Winnie-the-Pooh">
<p>Did you ever stop to think, and forget to start again?</p>
</blockquote>
<p>As A.A. Milne said, <q>Some people talk to animals. Not many listen though. That's the problem.</q></p>
```
## Abbreviations & acronyms
If you use an abbreviation or an acronym, then the `<abbr>` element can be used. A title attribute on the opening tag is used to specify the full term.

## citations & Definitions
When you are referencing a piece of work such as a book, film or research paper, the
`<cite>` element can be used to indicate where the citation is from.
```html
<p><cite>A Brief History of Time</cite> by Stephen Hawking has sold over ten million copies worldwide.</p>
```
The `<dfn>` element is used to indicate the defining instance of a new term.
```html
<p>A <dfn>black hole</dfn> is a region of space from which nothing, not even light, can escape.</p>
```

## Author Details
The `<address>` element has quite a specific use: to contain contact details for the author of the page.
```html
<address>
<p><a href="mailto:homer@example.org"> homer@example.org</a></p> 
<p>742 Evergreen Terrace, Springfield.</p>
</address>
```

## Changes to Content
The `<ins>` element can be used to show content that has been inserted into a document, while the `<del>` element can show text that has been deleted from it.
`<p>It was the <del>worst</del> <ins>best</ins> idea she had ever had.</p> `
The `<s>` element indicates something that is no longer accurate or relevant (but that should not be deleted). Visually the content of an `<s>` element will usually be displayed with a line through the center.

# CSS
* CSS1 was released in 1996 and CSS2 followed two years later. Work on CSS3 has been ongoing but the major browsers have already started to implement it.
* CSS works by associating rules with HTML elements by insert the `<link>` element as `<link rel="stylesheet" href="assets/css/style.css">` (External style sheet), there are several advantages to placing your CSS rules in a separate style sheet.
* You can also include CSS rules within an HTML page by placing them inside a `<style>` element, which usually sits inside the `<head>` element of the page (internal style sheet).
* An HTML page can use more than one CSS style sheet.
CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.
* The rules govern how the content of specified elements should be displayed. 
* CSS rule contains two parts selector & declaration. 

![selector-declaration](files/selector-declaration.png)

* There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document. Different types of selectors allow you to target your rules at different elements.

![types-selector](files/types-selector.png)

* You can add `!important` after any property value to indicate that it should be considered more important than other rules that apply to the same element


* CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon.

![property-value](files/property-value.png)




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

***

Go back

[Back](README.md)

