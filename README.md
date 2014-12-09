favicon-appicon-template
========================

Favicon and app icon PSD template with markup for iOS, Android and Windows

##Intro
This package includes a Photoshop template for generating favicon and app icon images at the various sizes required by iOS, Android and Windows. (As of 9/12/2014).

It also includes sample html, xml and json markup as required to implement the various image sizes and add to home screen functionality. You can extend on this, find out more at http://littlewebgiants.com/?p=853.

##Instructions
- Design a square icon image at minimum 310x310px resolution.
- Open up the Photoshop template and double click on the smart layer to edit it.
- Paste your image into the smart layer. Save and close the smart layer. You should now see your icon design repeated throughout the template.
- PSelect File>Save for Web, then click save in the dialogue box that opens. Select a location to save the files to. Make sure “save all user defined slices” is selected.
- PYou should now have 24 exported png files at the correct sizes in the folder you selected.
- PChoose your icon generator of choice and compile your favicon.ico from the relevant sizes (16×16, 24×24, 32×32 and 64×64 – the files are called favicon-1.png, favicon-2.png etc). I’ve found convertico.org to be a quick and easy online solution.
- POptional: for a more “native-like” experience, add in extra code to support full screen browsing, live feeds, or splash images.
- PAdd the contents of index.html into the <head> of your project.
- PAdd manifest.json and browserconfig.xml to your project root, or a subfolder.
- PAdd the image and ico files to your project root, or into a subfolder.
- PIf you have added the image, json or xml files to subfolders, update the html and the json and xml files to point to the correct file locations.
- You’re done!
