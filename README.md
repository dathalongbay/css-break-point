# css-break-point
css-break-point

Now let’s see some common breakpoints for widths of devices:  

320px — 480px: Mobile devices  
481px — 768px: iPads, Tablets  
769px — 1024px: Small screens, laptops  
1025px — 1200px: Desktops, large screens  
1201px and more —  Extra large screens, TV    
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

```
Rule : 
min-width tăng dần
max-width giảm dầm 
```

```
Common w3school
.example {
  padding: 20px;
  color: white;
}
/* Extra small devices (phones, 600px and down) */
@media only screen and (max-width: 600px) {
  .example {background: red;}
}

/* Small devices (portrait tablets and large phones, 600px and up) */
@media only screen and (min-width: 600px) {
  .example {background: green;}
}

/* Medium devices (landscape tablets, 768px and up) */
@media only screen and (min-width: 768px) {
  .example {background: blue;}
} 

/* Large devices (laptops/desktops, 992px and up) */
@media only screen and (min-width: 992px) {
  .example {background: orange;}
} 

/* Extra large devices (large laptops and desktops, 1200px and up) */
@media only screen and (min-width: 1200px) {
  .example {background: pink;}
}
```



```
// when the browser's width is between 600 and 900px, change the appearance of a <div> element:
@media screen and (max-width: 900px) and (min-width: 600px) {
  div.example {
    font-size: 50px;
    padding: 50px;
    border: 8px solid black;
    background: yellow;
  }
}
```

### https://codelearn.io/sharing/ap-dung-css-breakpoint-hieu-qua





