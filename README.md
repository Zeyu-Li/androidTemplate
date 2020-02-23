# Android Template 

## About

This is Android template that contains just a title and a button that toggles the display of an stylized "L"



### Notes for Android

If updating Kotlin, update the build.gradle version number in Gradle Scripts

**How to update the name:**

1. First go to the **Android Display**
2. In the gear icon on the projects structure, uncheck **Compact Middle Packages**
3. Drill down to java -> com -> #someDirName -> #someProjectName
4. Right click on the project and click <u>R</u>efractor -> Rename
5. Accept by clicking **Do Refactor** on bottom left corner in console view
6. Go to the build.gradle
7. Change **applicationId** to the new dir path (as a string)
8. Sync now
9. Go to values -> strings.xml and change app name

**Change Logo**

1. Right click **app**
2. New -> image asset (or vector asset)
3. Locate and tune

