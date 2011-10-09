# CSS3

## Border Radius

```scss
/* Mixin */
@include border-radius($radius, $topleft, $topright, $bottomright, $bottomleft);

/* Example */
@include border-radius(3px);
@include border-radius($topleft: 3px);
```

### Supports

* Webkit
* Mozilla
* Opera
* Internet Explorer 9+

## Box Shadow

```scss
/* Mixin */
@include box-shadow($x, $y, $blur, $color, $inset: false);

/* Example */
@include box-shadow(0, 0, 10px, rgba(0, 0, 0, .5));
```

### Supports

* Webkit
* Mozilla
* Opera
* Internet Explorer 9+

## Box Sizing

```scss
/* Mixin */
@include box-sizing($value);

/* Example */
@include box-sizing(border-box);
```

### Supports

* Webkit
* Mozilla
* Opera

## Transitions

```scss
/* Mixin */
@include transition($property: false, $time: 1s, $ease: linear);

/* Example */
@include transition(width, .35s);
```

### Supports

* Webkit
* Mozilla
* Opera

## Linear Gradient

```scss
/* Mixin */
@include linear-gradient($first, $last);

/* Example */
@include linear-gradient(#000, #111);
```

### Supports

* Webkit
* Mozilla
* Opera
* Internet Explorer 10+
* Internet Explorer 6-9

# Other

## Retina Graphics

```scss
/* Mixin */
@include hires-graphic($file, $type, $width, $height);

/* Example */
@include hires-graphic('logo', 'png', 200px, 120px);
```