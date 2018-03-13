# AndroidProject
This is a 2D mini pixel style game developed on Android Studio 3.0 for the module CS385 Moble Application Development. 

"Snake" is a mini mobile game that you can control the direction of a virtual snake (a green moving bar) to eat the "food" (a green stroke
square)by just tapping the phone screen.

When the head of snake touch the food square, it will lengthen the snake body by one food’s width. The “food” will disappear after eaten 
and appear randomly around the screen. Each sucessful eaten is 10 scores and the total scores is shown on the buttom of the scrren. The goal
is get the scores as high as possible and avoid "eat"(touch) snake body when it moving or run into the "wall"(bounday line). Both situation 
will lose the game and the restart hints will show on the screen – “Game Over! Please Try Again!”. Player can restart it by tapping the screen.

    Development Environment:
1. Android Studio 3.0
2. Java (programming language)

    (Key Libraries)
    
   android.graphics
   
   android.view.MotionEvent
   
   android.view.WindowManager
   
   android.os.Handler
   
   android.os.Message
   
   java.util.ArrayList
   
   
Please into ./app/src/java/com/example/android/snakenew check 3 java files -- SnakeView.java, MainActivity.java, SecondActivity.java
   
   
   
