# UnityCodeUtils
A script for Unity written is C# language which contain a lot of functions to help Unity developers with the code.

# READ BEFORE USE IT
# How to use this file
To use this script you can simply put the code into a script (pay attention because the namespace MUST be equal to the name of the script in the Unity game editor) and then put it into an object (if you put it on the main camera you can simply type "Camera.main.GetComponent<CodeUtils>()" when you make the reference to the script you should store it as a variable). 
When you need a function you MUST call it from the variable (ex. "CodeUtils.function();") and add the prefix 3D or 2D depending by the game you are making, then you add the variables that the function need to work and if in the description you find something like "This script return a" [type of value (ex. Raycast, int, bool...)] "value that you can use with" [name of the script] you must store the result of the function calculation into a variable that can store it (ex. if the type of value that the function return is a boolean you MUST store it in a boolean variable) and then give it to the script that need this value.
