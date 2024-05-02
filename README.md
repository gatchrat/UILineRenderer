# UILineRenderer
The built-in Linerenderer doesnt work if the canvas is set to Overlay render mode.
This script adds this functionality in the form of an alternative linerenderer.
## Gow to use
1. Create a Canvas and set the Render Mode to "Screen Space - Overlay"
2. Add the UILineRenderer script to any object inside the canvas that has a Canvas Renderer and Rect Transform
3. Add points either via code on Runtime, in Editor by changing the Point list, or using the "add points in Scene View" action

## What this fork adds
Mainly adds the ability to add points by clicking in the scene view, similar to the built in linerender.
Also adds the Canvas renderer as required, to prevent confusion.
