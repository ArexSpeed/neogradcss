Welcome to the neogradcss wiki!
This is a simplified version of docs for more details check https://neogradcss.web.app/docs

## Get Started

NeoGrad is a SCSS library and CSS code generator for creating buttons and divs with effects on your website. You can start using NeoGrad by downloading the code from this github and add it to your projects or you can use our Builder. You can choose your effect by clicking on the following steps and copy code and add to your css file without downloading anything.

If you choose to use NeoGrad by download you can add only one line code for your button in the class name. This code looks like this:

`<button class='btn btn-rect-4 btn-round-2 btn-neograd color-blue'>Button</button>`

The code is created in this easy following steps:

`class='btn-shape-size shape btn-radius-size-radiusType of radius btn-type color-colorName'`

All code for NeoGrad is available on this Github you can download this code and start creating

When you want to use NeoGrad without downloading additional files, just use the Builder which generates the code for you to copy. You can then edit it according to your own ideas

Example of generate code for blue gradient button

`.button {width: 150px; height: 75px; border-radius: 5px; color: #000; background: linear-gradient(to left, hsl(218, 100%, 68%), hsl(218, 100%, 48%)); border: none; transition: all 200ms ease-in-out; } .button:hover { box-shadow: inset -3px 3px 10px hsl(218, 100%, 68%), inset 3px -3px 10px hsl(218, 100%, 48%); }`

Check out the next steps of the documentation to see what NeoGrad offers.

## Shapes

NeoGrad has 4 type of shape which you can use.

Rectangle, long rectangle, square, circle

Chose your shape and add at the beginning of your code

`<button class='btn btn-square'>Square</button>`
`<button class='btn btn-rect'>Rectangle</button>`
`<button class='btn btn-long-rect'>Long Rectangle</button>`
`<button class='btn btn-circle'>Circle</button>`

For every shape, you have to choose the size. You can do it by adding a suffix to your shape code f.e `btn-square-4`

**Sizes** are available in 7 types:
- Mini (30px)
- Little (50px)
- Small (75px)
- Medium (100px)
- Big (150px)
- Large (200px)
- Huge (300px)

## Radius

If you want to round your button you can add a rounding size by adding the `btn-round` plus size `btn-round-3` class

Sizes of radius are according to table:
0px
2px -> `btn-round-1`
5px -> `btn-round-2`
10px -> `btn-round-3`
20px -> `btn-round-4`
50px -> `btn-round-5`
75px -> `btn-round-6`
100px -> `btn-round-7`

You can also choose a type of radius by adding suffix to your btn-round-(size)-type

You can choose one of 11 radius type:
Name	class
Normal	
Double1	-double1
Double2	-double2
Top	-top
Bottom	-bottom
Left	-left
Right	-right
Corner1	-corner1
Corner2	-corner2
Corner3	-corner3
Corner4	-corner4

## Types

The most important stage when you choose an effect for your buttons. At this moment are 30 effects to select.

You can add effect to your button by adding `btn-effect` to your class

Name	class
normal	- btn-normal
neograd	- btn-neograd
neograd reverse -	btn-neograd-r
gradient -	btn-grad
gradient radial -	btn-grad-radial
solid -	btn-solid
solid border -	btn-solid-border
neon -	btn-neon
neon border -	btn-neon-border
neon reflex -	btn-neon-reflex
border move -	btn-border-move
border move light -	btn-border-move-light
slide left -	btn-slide-left
slide right -	btn-slide-right
slide down -	btn-slide-down
slide up -	btn-slide-up
slide middle-in -	btn-slide-middle-in
slide middle-out -	btn-slide-middle-out
slide center-in -	btn-slide-center-in
slide center-out -	btn-slide-center-out
slide circle -	btn-slide-circle
behind border -	btn-border-behind
behind shadow -	btn-shadow-behind
double border -	btn-double-border
double border2 -	btn-double-border2
hide border -	btn-hide-border
surround border hover -	btn-surround-border-hover
pulse -	btn-pulse
pulse fast -	btn-pulse-fast
move -	btn-move

## Colors

The final stage, add colors for your button. Pick from 12 primary colors plus 3 additional colors for every which give you 48 colors to select or even more if you want to edit it by yourself

Primary color are: _green, blue, red, violet, yellow, orange, pink, black, white, gold, silver, brown_

The prefix for colors are: _light, dark, neon_

That's mean you can choose 4 versions of one color for example blue:

_blue, lightblue, darkblue, neonblue_

If you want to add color to a button just add at the end of class the color name `color-green`

You can add one or two colors as you need following by:
`color-firstColor`
`color-firstColor-secondColor`
