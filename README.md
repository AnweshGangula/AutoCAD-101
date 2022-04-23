# AutoCAD-101
Basic AutoCAD plugin using C# .NET 

Steps to Run the Code:

1. Open the project (.csproj) in Visual Studio
2. Click "Build Solution" under Build menu in ribbon (Ctrl+Shift+B)
3. "bin\debug" folder will be create under you root directory
4. Make sure that the "bin\debug" folder contains a ".dll" file with the name of your project.
5. Open AutoCAD and create a new blank drawing
6. Type in "NETLOAD" command which lets you load the plugin you build above in step 4
7. Choose the ".dll" file from the "bin\debug" folder
8. Hit Open - the plugin will be loaded

Test the Plugin:
1. Draw a Rectange of any dimension
2. Type "SelectObjectsOnScreen" command in AutoCAD and hit enter
3. Choose the Rectange that you drew in step 1 & hit enter
4. The Bounds of the rectangle will be displayed in a pop-up.
