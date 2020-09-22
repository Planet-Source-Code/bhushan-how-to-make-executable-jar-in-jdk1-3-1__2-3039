<div align="center">

## How to make executable jar\. in JDK1\.3\.1


</div>

### Description

Creting executable jar. in JDK1.3.1.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Bhushan\-](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/bhushan.md)
**Level**          |Intermediate
**User Rating**    |4.0 (64 globes from 16 users)
**Compatibility**  |Java \(JDK 1\.2\)
**Category**       |[Classes](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/classes__2-83.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/bhushan-how-to-make-executable-jar-in-jdk1-3-1__2-3039/archive/master.zip)





### Source Code

<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<meta name="GENERATOR" content="Microsoft FrontPage 4.0">
<meta name="ProgId" content="FrontPage.Editor.Document">
<title>New Page 1</title>
</head>
<body>
<p>&nbsp;</p>
<p><b><font size="4" color="#663300">How to make executable jar files in JDK1.3.1?,<br>
I can make jar in JDK 1.3.1 but when I developed a package in java(application) I was Unable to make executable jar.?</font></b><br>
<br>
<b>Instructions for creating an Excecutable .jar file</b></p>
<p><br>
<font size="4" color="#0066CC">Make or modify the Manifest.MF to YourManifest.MF.<br>
1) YourClassNameWithMain is the class name (case sensitive)without .class extention<br>
2) No extra spaces following the YourClassName withMain.<br>
<br>
	Manifest-Version:1.0<br>
	Main-Class: YourClassNameWithMain<br>
	Created-by:1.2(Sun Microsystems Inc.)<br>
	On Command line : type the following<br>
jar cvfm YourJarFileName.jar YourManifest.MF*<br>
or<br>
jar cvfm YourJarFileName.jar YourManifest.MF -C classes yourClassPath<br>
Drag-drop the YourJarFileName.jar to your desktop double click it, it runs<br>
If your program only has System.out.println ("whatever"); statements, it will<br>
display nothing. The same will happen when you run it useing java at command line&nbsp;<br>
You need some windows code to see it run<br>
Instructions for creating a .jar file<br>
jar utility comes with your JDK1.2.2 It compresses your<br>
file similar to zip utility, and more Java.<br>
You can use it on any machine installed JDK<br>
Create a folder name it anything<br>
Make that folder your current directory<br>
put all your files for turning in (do not put any extra)<br>
in that directory.<br>
Be sure to put your html file, if there is one<br>
At your dos prompt, while you are in the directory that you created , type in:<br>
jar cvf Prj02.jar*<br>
This will take ALL the files in the directory including&nbsp;<br>
subdirectories and place them in a .jar file Prj02 that can be<br>
 replaced by any of your desired jar file name.<br>
To test it, you can extract the contents of jar file by typing:<br>
jar xvf Prj02.jar</font><br>
<br>
<font color="#FF9900" size="4">Some user posted Query is on this location in my
codes so this is answer.<br>
<br>
<a href="http://www.planet-source-code.com/vb/scripts/ShowCode.asp?txtCodeId=3035&amp;lngWId=2">http://www.planet-source-code.com/vb/scripts/ShowCode.asp?txtCodeId=3035&amp;lngWId=2<br>
</a><br>
<br>
</font></p>
</body>
</html>

