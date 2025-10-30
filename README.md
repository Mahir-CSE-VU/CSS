# css

- Link
 ```css

  <link rel="stylesheet" href="">    at first link html

```

- Id
 ```css
  <div id=""></div>

  call id  #id name{}

```

- Class
```css

<div class=""></div>

call class .class name{}     Recomanded

```

- Background - color
```css

color:;       for  font color
background-color: ;    for background color
background-image: url();    for backgrounf image

background-repeat:repeat-x ;
background-repeat:repeat-y ;
background-repeat:no-repeat ;         for  repeat 
background-repeat:no-space ;
background-repeat:round ;

 background-size: cover;       cover all
 background-size: auto;        auto
 background-size: contain;     best  quality   
 background-size: px   px  ;   wish

background-position: ;( top,right,left, bottom center etc)     bg position

background-attachment: ;( fixed,scroll,local,scroll local,local scroll)

background: ; ( color , image prapet , attacment, position)  

```

- Padding Margin Border (Box Model)

```css

*{
padding: 0px;
                       for remove broser margin and padding
margin: 0px;   
}

padding: 20px 3opx 40px 30px; ( top right bottom left )
padding: 20px 3opx ; ( top bottom , right left )
padding: 20px; ( All Side )

margin: 20px 3opx 40px 30px; ( top right bottom left )
margin: 20px 3opx ; ( top bottom , left right)
margin: 20px  ; ( All Side )

border: 2px solid red;  ( Border width , Border style , Border color)
border-style:  (solid ,dotted,dashed,double,none etc.)

border-radius: ;  for curve

margin collaps       alwayes pioroty big one


box-sizing: ;(border-box , content-box)      1 box = 2nd box = border box , 1st box < 2nd box = content box  

```

- Display-Fonts
```css

display: ; (inline , block,inline-block,none)

visibility: hidden;

text-decoration: ; (underline ,  underline dotted , overline red , none etc.)

text-transform:  ; (capitalize,upercase,lowercse etc)

line-height: ;     use for incrise or dicrise gape of two line

text-indent: 50px;  firt word move forword

letter-spacing: 10px; space letter

font-variant: small-caps; 

font-size: ;
font-family: monospace;

font add  = google fonts  than copy font link and pest it head than copy font-family pest it css
font-style: ;  (itlic , oblique 40deg)
font-weight: ;  mota chikon   

```

- Size Position List
```css

font-size:2(em)    em= father font-size* given em size
font-size:2(rm)    rm= html font size* given rm size

height: 50vh     it's cover device 50 % hight
wedth: 50vw      it's cover device 50 % wedth
 
min-height:
max-height:
min-wedth:
max-wedth:

```
- Position
```css

static: ; default posision
relative: ; top,lft,right,bottom can use
absolute: ;     follow non-static parent command 
fixed: ;   position fixed
sticy:    fixed nav ber(any box)
z-index: ;

```

- List
```css

list-style: circle,squre,etc,url(),inside,outside.


```

- Flexbox
```css

float: ; (left right)
clear: ;(left right)

display:flex; insalization
flex-direction: ; (column,row,row-revers,column-revers)
flex-wrap: ; (wrap,wrap-revers)
justify-content: ; (baseline,center,left,right etc.)
align-items: ; (baseline,center.start,end,flex-end, etc.)
align-content: ;  same as align-items it's remove space.
align-self: ;    slf position control    
order: ;  box position number.
flex-grow :  incrise wedth.

```
- CSS Grid
```css

display:grid;
grid-template-columns: ;
grid-template-rows: ;
grid-row-gap: ;
grid-column-gap: ;
grid-gap: ;
grid-row: 1/3;
grid-column: 1/3 ;

 @media screen { }
```






































