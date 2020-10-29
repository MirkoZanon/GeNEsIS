# GeNEsIS - GEnerator of Numerical ElementS Images Software
This is a custom program written in Matlab (Matlab R2019a, The MathWorks Inc., Natick, Massachusetts, USA), using Appdesigner. 
A supplemtary tool of this program uses also Psychtoolbox-3 (the Psychophysics Toolbox extensions - Brainard, 1997; Pelli, 1997; Kleiner et al, 2007).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

With this program it is possible to create, and present on screen, stimuli with different numerosity and controlled physical characteristics, in particular it is possible to costraint:
-   R = radius, i.e. the characteristic dimention of the elements
-	TA = total area, i.e. the overall elements' surface
-	TP = total perimeter, i.e. the overall elements' contour length
-	ID = inter distance, i.e. the mean distance between all possible pairs of elements' centers (not defined for 1 element)
-	CH = convex hull, i.e. the area of the smallest convex polygon containing all the elements
-	D = density, i.e. the number (n) of elements divided by the occupied area (D=n/CH)

The whole program is structured in three different steps:

1.	a. GeNEsIS_create.mlapp
    Create controlled positions for your stimuli (CH, ID)

    b. shapesGenesis.mlapp
    Create controlled shapes for your stimuli (TA, TP)

2.	GeNEsIS_save.mlapp
    Customize your stimuli (colors, effective dimension) and save the final images

3.	GeNEsIS_display.mlapp
    Perform classical experiments of habituation or discrimination presenting your images on screen in an automatized way

GeNEsIS.mlapp provides an user-friendly interface to directly access all the tools and tutorials.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
RUN THE PROGRAM
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Requisites:
- Matlab
- (Psychtoolboox-3)

Make sure to have a recent version of Matlab; open it and set the proper working folder containing all the files of this program (GeNEsIs.mlapp, GeNEsIS_create.mlapp, shapesGenesis.mlapp, GeNEsIS_save.mlapp, GeNEsIS_display.mlapp and eventual Matlab files you will save during your work). 
Moreover, if you want to perform the final experiment (present the stimuli on screen with GeNEsIS_display), you need to install Psychtoolbox-3 (http://psychtoolbox.org/).

In order to open the programs just drag and drop the file of interest in the Matlab terminal.
You can simply use the main menu GeNEsIS.mlapp to access all the tools and tutorials in a fast way.
(If instead you want to visualize and modify the code, type ‘appdesigner’ in Matlab terminal and open the file of interest in the Matlab program that will appear).

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

In the graphic interface there are info buttons linking to detailed tutorials; you can find the whole tutorial also in the GeNEsIs folder. Read it carefully in order to use the program in an efficient way.
Good work!

If you find some bugs or you have suggestions to improve the program, please contact me: mirko.zanon@unitn.it

