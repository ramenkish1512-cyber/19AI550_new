# Ex.No: 2  Welcome Script in Unity
### DATE: 31/7/26                                                                           
### REGISTER NUMBER : 212225240116
### AIM: 
 To learn the basic scripting in Unity and print welcome message in Console window. 
### Procedure:
1. Start the program
2. Open the Unity hub and Create a new 3D project
3. In Assets window, create the new folder and name it as Scripts
4. Create a new script with file name as FirstScript
5. Open the Script and print message "Welcome to Unity" inside the start function
6. Save the script
7. Create a new 3D game object in Hierarchy window and name it as 3DObject.
8. Add the component Firstscript in inspector window of 3Dobject.
9. Run the program
10. Stop the program.
### Program 
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
public class FirstScript : MonoBehaviour
{
    // Start is called before the first frame update
    void Start()
    {
        print("Welcome to Unity");
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```
### Output:

<img width="1267" height="716" alt="WhatsApp Image 2026-07-31 at 14 19 57" src="https://github.com/user-attachments/assets/010030af-c54a-43e0-bd19-82bbc4f08cf4" />


### Result:
Thus the welcome script was printed on Console Window  sucessfully.

