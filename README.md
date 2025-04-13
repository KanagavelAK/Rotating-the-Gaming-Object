# Rotating-the-Gaming-Object

## Aim:
To develop a 3D application for rotating the gaming objects in unity.
## Algorithm:
### Step1:
Start
### Start2:
Click File -> Scene -> Select the scene -> Save as-> New folder(Scenes)-> File name (Expno1)
### Start3:
Click Hierarchy -> 3DObject -> Cylinder
Hierarchy -> 3DObject -> Capsule
Hierarchy -> 3DObject -> Text
Hierarchy -> Effects -> Particle system
### Start4:
Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Cylinder)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Cylinder to the plane and release the mouse

Create a folder in project and name as Materials
Material folder -> Create -> Material (Name: Capsule)
Inspector ->Surface Inputs ->BaseMAp (Choose the color)
Drag the Capsule to the plane and release the mouse

### Start5:
Click Hierarchy -> DirectionalLight
Inspector -> Change the color to white (255,255,255)

### Start6:
Create a folder name Coding and create a C# file to add the coding in it.

### Start7:
To add our C# Script file to our selected object, click on the C# Script file and drag it to our selected objects in the Hierarchy window nad run the application.

### Start8:
Stop

## Program:
```c
Developed by: Kanagavel A K
Reg no: 212223230096

using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Rotate : MonoBehaviour
{
    public Vector3 rot=new Vector3(1,0,0);

    void Update()
    {
        transform.Rotate(rot);
    }
}

```

## Output:
![Screenshot 2025-04-13 201035](https://github.com/user-attachments/assets/504d6d6f-85e4-448d-8618-753290d0453d)


## Result:
Thus a 3D application for rotating the gaming objects in unity is developed successfully.
