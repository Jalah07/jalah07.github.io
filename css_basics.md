## What is CSS
CSS, otherwise known as Cascading Style Sheets allows you to make your websites look more appealing visually. CSS is responsible for visual structure, layout, and overall visuals. CSS is one of the main technologies for the web.

## Why Is CSS so important?
CSS makes the user have a better experience because you can change fonts, font size, font color, and more.

## Pros of CSS

- Faster page speed
- Better UX
- Faster to develop
- Easy to change the format
- It is cross compatibile


## CSS Syntax

### Example Code
`<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<div id="heading">
<h1>This is a Heading</h1>
</div>

<p>This is a paragraph.</p>

<h1>Hello</h1>
</body>
</html>`



` h1 {
    color: blue;
    font-size: 22ems;
    font-family: "Times New Roman", Times, serif;
} `

^ This will apply to all the h1(s) in the HTML file. It will make the text color blue, the font size to be 22ems, and font family to be Times New Roman.

However, you can add even specifally with more selectors. 

`#heading h1 {
    color: pink;
}`

^ This would only change the heading with an id of heading.

## CSS Selectors

1. Elements are like  `h1`, `p`, or  `div`.
`<h1> Heading </h1>`
`<p id='para-1'> This is a paragraph </p>`
`<div><p>Cool</p></div>`
2. Classes are way to select a HTML element and each element can have multiple classes,
`<div class='container'>  
    <h1> Hello </h1>  
</div>`
3. IDs are similar to classes, however they can only be applied to one HTML element.
`<div>  
    <p id='para-1'> This is a paragraph </p>  
</div>`