# Kistagangen VR 

This is the Unity project for a simple VR visualisation of Kistagangen in Kista, Sweden using GVR for Google Cardboard.

The 3d model was built with Blender. 

For the skybox I used sky5x (https://www.assetstore.unity3d.com/en/#!/content/6332) and a modified version of JuppOtto's script for autowalk (https://github.com/JuppOtto/Google-Cardboard/blob/master/Autowalk.cs). 

To run the visualisation on iphone using Xcode do the following: 

1. In Unity go to File > Build Settings and choose iOS.
2. Go to Player Settings and on "Allowed Orientations for Auto Rotation" make sure only "Landscape Left" is checked. On "Other Settings" introduce a single Bundle Identifier with the following pattern: com.someOrgName.someProjName
3. Connect your iOS device to your computer. 
4. Build and Run the project
5. Once Xcode opens, if you haven't configured it, you are likely to have two Dependencies errors. To solve them, do the following: 
  a. Go to Settings>Accounts and Add an Apple Id 
  b. On the Apple ID info go to Manage Certificates and create iOS development certificate. 
  c. Go to the Project General Settings and in Signing add your team (Personal team with your name).
7. Build and run the project again. Wait until it finishes. 
8. Go to your device and on Settings>General>Device Management>Developer Apps choose to trust the app's certificate. 
9. Run

Built using Unity 5.5.2 