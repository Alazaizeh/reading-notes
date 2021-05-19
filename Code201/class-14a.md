
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
# Transitions
There are four transition related properties in total, including `transition-property`,` transition-duration`, `transition-timing-function`, and` transition-delay`. 

## Syntax

```
div {
  background: #ccc;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
```
# Animations
when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

## Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

### Example

```
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```
## Animation Name
Once the keyframes for an animation have been declared they need to be assigned to an element. To do so, the animation-name property is used with the animation name, identified from the @keyframes rule

## Animation Duration, Timing Function,Iteration & Delay
```
.stage:hover .ball {
  animation-name: slide;
  animation-duration: 2s;
  animation-timing-function: ease-in-out;
  animation-delay: .5s;
  animation-iteration-count: infinite;
}
```
## Animation Play State
The `animation-play-state` property allows an animation to be played or paused using the `running` and `paused` keyword values respectively.
### Example
```
.stage:active .ball {
  animation-play-state: paused;
}
```
## Animation Fill Mode
The animation-fill-mode property identifies how an element should be styled either before, after, or before and after an animation is run. The animation-fill-mode property accepts four keyword values, including none, forwards, backwards, and both.

## Shorthand Animations
Fortunately animations, just like transitions, can be written out in a shorthand format.

### Example
```
.stage:hover .ball {
  animation: slide 2s ease-in-out .5s infinite alternate;
}
```
