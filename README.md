# temporal-typography
Web-based Temporal Typography API 

## Input
* Web-Audio Node
  * Analyser Node
    * time domain data 
    * frequency data (array) 
    * volume (1 value) 

## Output 
* position
  * x-y-z position 
* size 
  * height, width, space
  * linespace, letterspace ( alinged to where? )
* rotation
  * x,y,z axis
  * Anchor point
* range (where specifically do you want the visualization to be? All or partially?)
  * letter index
* font color
  * RGB
  * Alpha
* Background Color

## Processor Node? 

* How can we add GLSL flexibility accessible to plain users? 

## Intial Options 

* Font Family
* Line space
* Alignment (Left, Right, Center) 
* Font Type (Bold, Italic, Underlined, etc) 
* Font Color

## Ideas

* Build Script in Live Programming Fashion (Immediate result on the side) 
* Let the user have their own graphics (in the background or foreground) for sure. 
