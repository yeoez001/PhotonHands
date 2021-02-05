# Photon-supported Hand Tracking
Basic project that supports hand tracking using the Oculus Quest and a multiplayer experience using Photon.  

## Photon Setup
1. Create a [Photon](https://www.photonengine.com/) account and go to Dashboard.
2. Create a new app.
3. Copy the __Application ID__ .
4. Open the Unity project and navigate to __Window > Photon Unity Networking > Highlight Server Settings__.
5. Open the inspector and navigate to __Server/Cloud Settings > App Id PUN__.
6. Paste the Application ID into the text field. 

## Application Setup
Push the application to the Oculus Quest device with Oculus Link by __Oculus > OVR Build > OVR Build APK and Run__. For multiple devices to connect to the same room, ensure the same __Application ID__ is used in the Photon setup.
On a PC, the application can be played and viewed from the Scene or Game view. Whilst the application is running, the __Camera__ Gameobjects under __Cameras__ can be enabled for a four-way view of the scene from the Game view. 
On the Oculus Quest device, if hand tracking stops working or your hands disappear from the scene, restart the application. 
