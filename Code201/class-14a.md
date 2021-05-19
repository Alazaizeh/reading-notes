
![google](https://cdn.iconscout.com/icon/free/png-512/css3-8-1175200.png)
# Transforms
Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

## Syntax

```
div {
    -webkit-transform: scale(1.5);
    -moz-transform: scale(1.5);
    -o-transform: scale(1.5);
    transform: scale(1.5);
}
```
## 2D Transforms
Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane.

## 2D Rotate
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees.
### Example
```
div {
  transform: rotate(20deg);
}
```

## 2D Scale
Using the scale value within the transform property allows you to change the appeared size of an element.
### Example
```
div {
  transform: scale(1.5);
}
```
## 2D Translate
The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
### Example
```
.box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}

```

## 2D Skew
The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.
### Example
```
.box-1 {
  transform: skewX(5deg);
}
.box-2 {
  transform: skewY(-20deg);
}
.box-3 {
  transform: skew(5deg, -20deg);
}

```
