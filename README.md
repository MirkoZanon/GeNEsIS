# GeNEsIS - Generator of numerical elements images software
This is a custom program written in Matlab 2019, using Appdesigner. 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------

With this program it will be possible to create stimuli with different numerosity and balanced characteristics, in particular it is possible to control:
-	TA = total area, overall elements area
-	TP = total perimeter, overall elements contour length
-	ID = mean distance between all elements centers (not defined for <2 element)
-	CH = convex hull defined by the elements centers disposition (not defined for <3 elements)
-	D = density defined as number of elements divided by the occupied area (CH)

The whole program is structured in three different steps:

1.	a. GeNEsIS_create.mlapp
    Create balanced positions for your stimuli (CH, ID)

    b. shapesGenesis.mlapp
    Create balanced shapes for your stimuli (TA, TP)

2.	GeNEsIS_save.mlapp
    Visualize your stimuli and set graphical properties (colors, effective dimension)

3.	GeNEsIS_display.mlapp
    Perform classical experiments of habituation or discrimination presenting your images on screen in an automatized way

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------
RUN THE PROGRAM
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Requisites:
- Matlab
- (Psychtoolboox)

Make sure to have a recent version of Matlab; open it and set the proper working folder containing all the files of this program (GeNEsIs.mlapp, GeNEsIS_create.mlapp, shapesGenesis.mlapp, GeNEsIS_save.mlapp, GeNEsIS_display.mlapp and eventual Matlab files you will save during your work). 
Moreover, if you want to perform the final experiment (present the stimuli on screen with GeNEsIS_display), you need to install Psychtoolbox (http://psychtoolbox.org/).

In order to open the programs just drag and drop the file of interest in the Matlab terminal.
You can use simply the main menu GeNEsIS.mlapp to access all the tools in a simple way.
(If instead you want to visualize and modify the code, type ‘appdesigner’ in Matlab terminal and open the file in the program that will appear).

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------

In the graphic interface there are info buttons linking to detailed tutorials; you can find the whole tutorial also in the GeNEsIs folder. Read it carefully in order to use the program in an efficient way.
Good work!

If you find some bugs or you have suggestions to improve the program, please contact me: mirko.zanon@unitn.it

