# ScreenCaptureToBase64

## Objective:

ScreenCaptureToBase64 is a custom-java-action used for Convert the Screen Shot to Base64 focused on Storing the Content in String Format inside Mendix for transportation Purposes.
Base64 Captured Screen Shot Can Converted into System.Image or System.FileDocument Object Using the Community Commons Module Java Action Base64Decode.
Dependencies:
Studio pro version – 9.12.10
Configuration:
To get started with ScreenCaptureToBase64, a Java Action, first download the ScreenCaptureToBase64 Module from Mendix MarketPlace.
Create a Microflow with the ScreenShotEncodeBase64 Java Action to capture the ScreenShot and convert into Base64 Content.
You can Either Save this content in a String Attribute of desired Entity Object,  And Convert the Base64 String to System.Image or System.FileDocument based on your requirement.

## Screenshots:
 ![image](https://user-images.githubusercontent.com/26872174/222737674-6e883016-1422-4151-ba4e-bb479f5699fd.png)
![image](https://user-images.githubusercontent.com/26872174/222737725-991803fe-9ca0-4de2-8826-c167277238e3.png)
![image](https://user-images.githubusercontent.com/26872174/222737764-a12857a8-161f-4c89-9e3e-f3f9b7bb5f30.png)
![image](https://user-images.githubusercontent.com/26872174/222737818-c92d6cdc-1f0d-436c-9810-57256eb10645.png)  
	Sample Use of ScreenShotEncodeBase64 in Screen Shot to Image Object Microflow
  ![image](https://user-images.githubusercontent.com/26872174/222739232-fc2d96b1-f607-4108-9caf-c872f671433e.png)

## USEME:
	This Folder Contains a Java Action ScreenShotEncodeBase64 Which User Can Use to Convert Current Screen into Base64 String.
	And It Contains a Custom Layout Which includes a Screen Shot Badge on the Right Side, which can be Used for ui purpose to Trigger the Action to Take Screen Shot.
 ![image](https://user-images.githubusercontent.com/26872174/222737931-5471724f-8ab3-46ec-8b87-3f7d86bc3d82.png)

	This Folder also Contains a Snippet Which can be used as Screen Shot badge Clickable near the Scroll Bar.(Check out the Custom_Layout for Ref)
## Note:
Make Use of the Microflow SUB_ScreenCaptureToBase64 in your Microflow to trigger the Java Action to Took the Screen Capture and Covert into Base64 String.
