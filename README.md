# Kistagangen VR 

This is a simple VR visualisation of Kistagangen in Kista, Sweden. 

The 3d model was built with Blender and integrated with the GVR SDK using Unity. 
This project includes a build for iOS to be run with Xcode (tested with version 8.3.1). 
The Unity and Xcode projects are included. 

1. Connect your iOS device to your computer. 
2. Open the project in Xcode (Kistagangen_build_#)
3. If you haven't configured Xcode, do the following:
  a. Go to Settings>Accounts and Add an Apple Id 
  b. On the Apple ID info go to Manage Certificates and create iOS development certificate. 
4. Build and run the project. 
5. You will probably get two Dependencies errors related to Signing. 
6. To fix this go to the Project General Settings and in signing add your team (Personal team with your name).
7. Build and run the project again. Wait until it finishes. 
8. Go to your device and on Settings>General>Device Management>Developer Apps choose to trust the app's certificate. 
9. Run

*Might need to install GVR for iOS, not sure. 
