# ATD
Animated Text's Decorations is a ***CSS Library*** who adding small animations on text. ***Sorry for my bad english, if you found some mistakes or error thanks to open an Issue ticket***

## Demo

You can try it [here](https://plixe.github.io/ATD/)

## TO-DO

* Increase esthetic of demo page !
* Automation with JS !
* Documentation translations !

If you have any idea it'll be a pleasure to add it to the TO-DO list ! 

## Getting Started

You can use ATD with two different way

### Getting the file

Download the `atd.css` [here](https://github.com/Plixe/ATD/tree/master/docs) and add this code in your html

```html
<head>

 <link href="path/atd.css" rel="stylesheet">

</head>
```

### Use direct link

You can use ATD directly without download the css file with adding this code in your html. I highly recommend this method because you'll always have
the last version.

```html
<head>

 <link href="https://raw.githack.com/Plixe/ATD/master/docs/atd.css" rel="stylesheet">

</head>
```

## How use it ?

### ATD-DATA

To use ATD you have to add attributes in html tag.

```html
<h1 atd-data="underliner">Hello world</h1>
```

All datas :
* `backliner`
* `half-backliner`
* `overliner`
* `underliner`

### ATD-OPTION

You can add some extra options:

#### COLOR

You can change the color of the ATD

```html
<h1 atd-data="underliner" atd-color="white">Hello world</h1>
```

*But you have to define variable in your master css file. *Futures version will have best method*

```css

:root {

  --atd-white: #fffffe

}

```

All colors can be defined :
* `white`
* `black`
* `red`
* `green`
* `blue`
* `yellow`
* `orange`
* `custom1`
* `custom2`
* `custom3`

#### ANCHOR

Anchor option change the begening point of the ATD:

```html
<h1 atd-data="underliner" atd-color="white" atd-anchor="left">Hello world</h1>
```

All anchors :
* `left`
* `center`
* `right`

#### WBEGIN

With this option, ATD begin at choosen percent.

```html
<h1 atd-data="underliner" atd-color="white" atd-wbegin="30">Hello world</h1>
```

All states :
* `10`
* `30`
* `50`
