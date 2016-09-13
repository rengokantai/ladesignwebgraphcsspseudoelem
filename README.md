### ladesignwebgraphcsspseudoelem
#####Creating a pseudo-element with CSS
::after, default = display:inline  
[::after test, with text & without text](https://jsfiddle.net/rengokantai/53mmg4u2/)  

#####Spacing and layout adjustments
make a box out of parent. use negative margin  

Restyling an unordered list
[li element,set display=block to eliminate buillet point](https://jsfiddle.net/rengokantai/u69y0f4k/)  
Add image before list item
```
li{
display:block;
position:relative;
padding: (set more left padding)
}

li:before{
  url:() no-repeat 0 0;
  content:'';
  display:block;
  height:
  width:
  background-size:20px 10px;
  position:absolute;
  top:
  left:
}
```
