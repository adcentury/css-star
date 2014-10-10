CSS Star
========

Use only css to draw a five-pointed star.

The position of the star is set by the center of it (which is also the center of its Circumcircle), so you can controll it precisely.

An [example](http://codepen.io/leilei/pen/lGyjo?editors=110) is available at [my CodePen](http://codepen.io/leilei/public/)

## Usage

- Copy **star.css** into your project directory

- Load css file in your `<head>` label

```html
<link rel="stylesheet" href="star.css">
```

- Generate star with a single div

```html
<div class="star" id="myStar"></div>
```

- Set the star's center position and circumcircle radius by css. ()

```css
#myStar {
	left: 50px;
	top: 50px;
	font-size: 50px;	/* use font-size to set the radius */
}
```

- Enjoy it!
