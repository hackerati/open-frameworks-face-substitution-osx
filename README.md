# OpenFrameworksFaceSubstitution
Working version of Face Substitution on Mac OS 

Note that I couldn't push the entire Open Frameworks folder due to file size. 

folder structure is

of_v0.8.4_osx_release --> addons (in which you have added ofxCv and ofxFaceTracker and worked out its build errors)
--> ofxFaceTracker --> This Folder.

Basically, I took an example project under ofxFaceTracker that was compiling correctly (example-advanced copy) and replaced the source code with FaceSubstitution repo. 

**Note that there's an "vector error" that crashes the program when you press up too many times and there's not enough images in the background. Tried to fix with variable manipulation but crashes nonetheless. Remember to put as many images in there as you want, and don't press up more than # of images. 
