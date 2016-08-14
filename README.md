# Tweakipedia
Course Name-Knowledge Processing Technologies. Integrating Twitter(dummy) with Wikipedia
Technology Used:
Java EE (Java 1.7) - Eclipse
Apache Tomcat 1.7

Importing Web archive (WAR) files:
Import WAR file into workspace, 
1.	Select Java EE perspective
2.	Select File ˃ Import
3.	In the Import dialog, select WAR file and then click next.
4.	Select WAR file from given folder.
5.	Click next 
6.	Click finish
7.	Configuring  additional JAR files in Eclipse:
Right click on project > Build Path > Configure build path > Add External Jars >Browse to folder created and include 5 JAR files (curvesapi-1.03.jar, poi-3.14-20160307.jar, poi-ooxml-3.14-20160307.jar, poi-ooxml-schemas-3.14-20160307.jar, xmlbeans-2.6.0.jar) ˃ Apply ˃ Ok
8.	Change the file path in “ReadTweets.java” 
Example:”E:\\KPT\\Project Twikification\\DataTwitter.xlsx”  
9.	Refresh the project
10.	Right click on project > Run as > Run on Server

Tomcat Configuration:

1.	If tomcat is not configured on system then at the time of running project it will ask to configure.
2.	Just follow the step.

Note:
1.	Clicking on a trending word will open Wikipedia page for that trend (Example: #squarespace links to https://en.wikipedia.org/wiki/Squarespace).
2.	Search box works only for words present in our database, so try something like ‘nyc’, ‘oscars’, ‘hurricane’ etc.

 
Android Application:
1.	“TweakipediaAndroidSourceFiles” contains the source files created for making the Android app (this can be imported in Android Studio)
2.	Tweakipedia.apk can be downloaded on any phone with Android OS

