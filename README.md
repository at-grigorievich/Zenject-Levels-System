# Zenject Levels System

It's a level control system in Unity using Zenject containers

Allows you to dynamically create levels using ScriptableObject.

[Download like unitypackage](https://github.com/at-grigorievich/Zenject-Levels-System/blob/main/Zenject%20Levels%20System.unitypackage)

Two types of level are supported: Runner like & Matrix NxM size

1) Drag prefabs from the Prefabs folder to the game scene
2) Create a level data ( Right-Click -> Create -> Levels -> New Linear Level / New Matrix Level )
3) Add created SO to Levels List ( Level Data folder )

# Example 1. Runner Like level:

Zenject and Non-Zenject types available

Only one axis:           
![alt text]( https://github.com/at-grigorievich/Zenject-Levels-System/blob/main/Screens/runnerlike.jpg?raw=true "Runner like 1")

Two axis:                    
![alt text]( https://github.com/at-grigorievich/Zenject-Levels-System/blob/main/Screens/runnerlike1.jpg?raw=true  "Runner like 2")

# Example 2. Matrix level:

Zenject and Non-Zenject types available

Constant height :           
![alt text]( https://github.com/at-grigorievich/Zenject-Levels-System/blob/main/Screens/matrix.jpg?raw=true "Matrix like 1")

Different height:                    
![alt text]( https://github.com/at-grigorievich/Zenject-Levels-System/blob/main/Screens/matrix1.jpg?raw=true  "Matrix like 2")

# Example 3. Static level:

Allows to create objects in the coordinates specified in the prefab
Zenject and Non-Zenject types available

![alt text]( https://github.com/at-grigorievich/Zenject-Levels-System/blob/main/Screens/staticI.jpg?raw=true "Static like")


Using: 
1. [2D Array in Editor](https://github.com/Eldoir/Array2DEditor)
2. [Zenject Framework](https://github.com/modesttree/Zenject)



