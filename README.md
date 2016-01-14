# openscad-box-tutorial

How to design parametric laser cut boxes with [OpenSCAD](http://www.openscad.org/)

# TODO:

* Write this tutorial

# Outline

## Part 1: Making a wall

* Make a cube W = 120mm ^ 3
* Use the thickness of wood T = 5.7mm
* Copy W to L
* Make the cube to a flat piece W x L x T
* Make it a module wall() and then call the module

## Part 2: Making walls

* Make another wall and rotate it 90 degrees
* Copy that wall and translate it by W
* Make another wall and rotate it 90 x 90
* Copy that and translate it
* Adjust them by T in the right direction to fit

## Part 3: Keeping tabs

* Cut out bottom tabs in thirds
* Cut out inverse tabs on bottom of sides
* Cut out side tabs on two sides
* Cut out inverse side tabs on other sides

## Part 4: The Flattening

* Explain why modules are separate from linear_extrude
* Lay out bottom and sides
* Laser kerf explanation and outset

## Part 5: Order confirmed

* Turning into an SVG
* Adjusting to Ponoko Inkscape template
* Uploading and setting materials

## Part 6: Putting it together

* Assembling the pieces
* Evaluating and improving kerf offsets
