## The picture element

[Source: Google Chrome](https://googlechrome.github.io/samples/picture-element/)

Go on the source and resize your browser... The image source change according to viewport size !

How does that work ?! Pretty simply actually:

```html
<picture>
  <source media="(min-width: 650px)" srcset="images/kitten-large.png">
  <source media="(min-width: 465px)" srcset="images/kitten-medium.png">
  <!-- img tag for browsers that do not support picture element -->
  <img src="images/kitten-small.png" alt="a cute kitten">
</picture>
 ```
