# ColorSwapShader
Unity project with a nice shader that can swap colors(black/white/red) and create dynamic colors inside the game

I am presenting the ColorSwapShader, a remake of this tutorial from YT from Francis Vace ( https://www.youtube.com/watch?v=VwDshEqwo7g 

Technically this works with two cameras and a quad receiving the output from the mainCamera, where the pixelCamera is capturing this output.
LIke this we can shader th whole screen withou afffecting the single gameobjects.
![paletteShader_cameras](https://user-images.githubusercontent.com/45642858/177634529-d4f546c7-8e22-4436-b9cf-13d48432c599.gif)

Then you can swap colors. In this example I used a black and white sprite and added a threshold to create a ligthing effect
![paletteShader_swapingColors](https://user-images.githubusercontent.com/45642858/177634538-8653aa22-2136-4d80-ad83-35038fc4ee1c.gif)

Have fun playing with this and feedback is welcome.
