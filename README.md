# CSS3

## Border Radius

```scss
@include border-radius($radius, $topleft, $topright, $bottomright, $bottomleft);
@include border-radius(3px);
@include border-radius($topleft: 3px);
```

## Box Shadow

```scss
@include box-shadow($x, $y, $blur, $color, $inset: false);
@include box-shadow(0, 0, 10px, rgba(0, 0, 0, .5));
```

## Box Sizing

```scss
@include box-sizing($value);
@include box-sizing(border-box);
```

## Transitions

```scss
@include transition($property: false, $time: 1s, $ease: linear);
@include transition(width, .35s);
```

# Other

## Retina Graphics

```scss
@include hires-graphic($file, $type, $width, $height);
@include hires-graphic('logo', 'png', 200px, 120px);
```