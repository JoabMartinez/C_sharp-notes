# C_sharp-notes
Here are all my notes for C# if I ever get stuck and/or learn something new.
References:
https://www.youtube.com/watch?v=tzq-DJeNIrU&t=19s

9_17_2018
Introduction

Key Terms -
Public - Accessable outside of the script. (can be seen elsewhere, can be seen in the inspector)
  ex. Public int health = 5;
Private - It's protected wihtin the script. It keeps it private in the script
  ex. Private int health = 5;
Integer (int) - A whole number. 
  ex. 5
Variable - It is just a name given to a storage area that our programs can manipulate. 
  ex. health
Float - a number with a decimal. 
  ex. 5.00
f - Declares the variable as a type of float. 
  ex. 5.00f
bool - It is used to declare variables to store the Boolean values which are true and/or false.
  ex. public bool trueorfalse = true;
GameObject - Allows me to put a Game Object within the inspector.
  ex. public GameObject player;
Awake() - References between scripts, initialisation
ex. Sets ammo for the enemy
Start() - Once script component is enabled
ex. Allows enemy to shoot
Update()
void OnTriggerEnter(Collider other)
  Collider is the class and other is the actual name we want to reference as.
Void - Will always be private
  ex. void NewDeath()
You can make a function public if you want it to be accessed outside of the script.
  ex. public void NewDeath()
  
 9_18_2018
 Trigger Events
