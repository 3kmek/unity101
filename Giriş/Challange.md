https://unity-connect-prd.storage.googleapis.com/20210506/913574fa-af65-4d95-abe8-d90282b27a83/Challenge%201%20-%20Starter%20Files.zip

## Bugs
1. The plane is going backward - **Make the plane go forward**
2. The plane is going too fast - Slow the plane down to a manageable speed
3. The plane is tilting automatically - Make the plane tilt only if the user presses the up/down arrows
4. The camera is in front of the plane - Reposition it so it’s beside the plane
5. The camera is not following the plane - Make the camera follow the plane
6. BONUS The plane’s propeller does not spin - Create a script that spins the plane’s propeller

## Hints
- Make the plane go forward Hint: Vector3.back makes an object move backwards, Vector3.forward makes it go forwards
    

- Slow the plane down to a manageable speed Hint: If you multiply a value by Time.deltaTime, it will change it from 1x/frame to 1x/second
    

- Make the plane tilt only if the user presses the up/down arrows Hint: In PlaneController.cs, in Update(), the verticalInput value is assigned, but it’s never actually used in the Rotate() call
    

- Reposition it so it’s beside the plane Hint: For the camera’s position, try X=30, Y=0, Z=10 and for the camera’s rotation, try X=0, Y=-90, Z=0
    

- Make the camera follow the plane Hint: In FollowPlane.cs, neither the plane nor offset variables are assigned a value - assign the plane variable in the camera’s inspector and assign the offset = new Vector3(30, 0, 10) in the code
    

- Bonus - Make the propeller spin Hint: There is a “Propeller” child object of the plane - you should create a new “SpinPropellerX.cs” script and make it rotate every frame around the Z axis.