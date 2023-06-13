========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "LibraryLogger.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.

========================
========================

LIBRARY LOGGER

*Open the application
*Log in your account , if you do not have an account click sign -up
*After logging in, go to logs and input the students who entered the library and click add
*If you want to update or delete a certain data, select a data and then update it or delete
*If you want to search a data,in a search icon just type the student id
*In a book details you can also add,update, and delete a book
*In the generate daily logs you can see there the reports where you can print an individual reports
*When clicking the logout the system immediately led you to the log in screen


DATABASE = MYSQL
SERVER = XAMMP

JARFILES:
Time Chooser.jar
jBcrypt-0.4.1.jar
jcalendar-1.4.jar
rs2xml.jar
