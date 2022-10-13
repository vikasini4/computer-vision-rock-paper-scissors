# Computer Vision RPS
Milestone 2

Creation of computer vision system via Teachable Machine 

This model can predict the output of the model by the shape of the hands. In order to get a proper result, the shape of hands is important and the number of images makes it more predictable for the user the output.

Milestone 3

Creation of an environment in order to manage the dependencies required to run the code. After all set, in order to check everything is all installed, had to run the keras model provided from Teachable-Machine.

Milestone 4

Manual version of Rock Paper Scissors game.

The prerequisite programs, including tensorflow, numpy, opencv(cv2), and time, were imported. A class called Rock, Paper, Scissors was made, and the following initialised attributes were used to track the game.

A winning structure function def who wins() was created so the code can decide a winner for each round. The camera's output will then be integrated with this function so that a matched "string" is selected within the function based on the camera's output.

Milestone 5

Using the camera of the computer to play Rock Paper Scissors game.

To enable the code to match the player's input to the trained model, a class list was created. It's essential to remember that the order of the categories on this list should correspond to the order in which they were entered into the Teachable Machine.

A function was developed to enable the code to decide which move the player is showing. Depending on how accurately the input from the camera matches the classes, the trained model outputs an array of four integers. The number chosen by the np.argmax(prediction[:0]) function has the highest chance of matching the player input. The player choice was then saved as a result of this decision. The user would be asked to choose again if the Nothing class was chosen.
