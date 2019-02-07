# SCSS SVG divider
A scss svg divider libary.

## Usage:

### Initializing

Download this repo and import it into your scss file.
````
@import 'svg-divider';
````
Then call the mixin.
````
@include create-svg(identifier <required>, color <initial: #fff | hex or rgb>, svg <initial: all | name of svg or list of svg names or all>, height: <initial: 80px>);
````
For a top divider use (without the curly braces).
````
.svg-divider.top.{svg name}-{your identifier}
````
For a bottom divider use (without the curly braces).
````
.svg-divider.bottom.{svg name}-{your identifier}
````

### Rotating

If the divider has not the wished rotation, can you change it using the follow classes.

#### Rotating the top divider.
About the y axis.
````
.top-rotate-y
````
About the x axis.
````
.top-rotate-x
````
About the x and the y axis.
````
.top-rotate-x-y
````

#### Rotating the bottom divider.
About the y axis.
````
.bottom-rotate-y
````
About the x axis.
````
.bottom-rotate-x
````
About the x and the y axis.
````
.bottom-rotate-x-y
````
