# CSS

```
1. CSS is used to style the HTML document so that it looks pretty.
2. One page can have several CSS to render different style of the page(for brower or printer) 
```

## CSS structure
```
p (selector:stands for thing to which the style apply)
{ 
  //style description
  font-size:(style defined by user) 44px(value of the style) ;
}
```
## CSS Common Unit

px: CSS pixel(96 = 1 inch)
% : percent of the parent element(the ancestor tag)
em: multiple of the current font size.
vw/vh: percent view port width/height
pt:point/picas(1/72 of 1 inch)
mm/cm/in: measurement

## CSS Selectors

id: ex: <p id ="header1"....> ; #header(refers to the spcific p){ //style decription}
class
Element type
Adjacent sibling: ex h+p the p immediately following h
General sibling: ex h~p all p following a h
Child
Descendant
Attribute
Pseudo-classes/-elements

## CSS Properties for tag
color
background-color
margin
padding
font-family : style of font
font-size
font-weight : boldness
text-align : left, right, center
float
display : inline(one next to other), block(one below to other), inline-block(inline with definable w/h), none
height : height of an element
width : width of an element
vh
vw
text-decoration
background-image
background-repeat
border

## box model
1.content->padding->border->margin(gap between border and other external element)
2.width and height both include margin
div{
  width: 320px;
  padding: 10px;
  border: 5px solid gray;
  margin: 0;
}

## link the HTML with CSS
<head>
  <title>Result</title>
  <link type="text/css" rel="stylesheet" href="stylesheet.css" />
</head>
