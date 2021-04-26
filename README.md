# UiPathAxe508
This github project has details on how to use a UiPath library and Axe Dev Tools plugin for google chrome browser to perform 508 compliance testing

As a Prerequisite, anyone using this project should already be aware of using UiPath for automation of their web application

In addition they need to address a few prerequisites described in the word document https://github.com/my2239/UiPathAxe508/blob/main/UiPath%20and%20Deque%20AxeDevToolsfor%20508%20testing.doc
Alternatively the PDF document can also be used to learn about prerequisites
https://github.com/my2239/UiPathAxe508/blob/main/UiPath%20and%20Deque%20AxeDevToolsfor%20508%20testing.pdf

I would expect anyone intending to use the UiPath Library Activity "PerformViusual508Scan" to go through the prerequisites above and download the package
https://github.com/my2239/UiPathAxe508/blob/main/AxeVisual508ScanLibrary.1.0.12.nupkg

After downloading the packge above they should import it to a UiPath project of their choice

Once these steps are completed, they should be able to call the Activity "PerformViusual508Scan" anytime passing just the folder where they would like their results. 
For Example:  "C:\automation\axe_visual_508_reports". 
The folder should already exist in the windows computer running the test and should have write acces privileges for the user running the test.
The path should be absolute and is NOT case sensitive.

As an example, a UiPath Process that performs 508 scan using the library above is included
https://github.com/my2239/UiPathAxe508/blob/main/CallAxeVisual508Scan.zip
Fell free to download this project and open it using Uipath Studio to learn and model your tests accordingly

If you would like to see how the package  AxeVisual508ScanLibrary.1.0.12.nupkg was built, I am including the source code for the UiPath Library
https://github.com/my2239/UiPathAxe508/blob/main/AxeVisual508ScanLibrary.zip

Please feel free to reach me at ymahesh@gmail.com if you have any questions
