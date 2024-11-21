# Children'sTherapy

## Purpose:

This project will have a libary of buttons corresponding to different objects
that kids can press to see a short video of the object as a reward. This is to
assist in children't therapy efforts and ideally it should be able to easily
expand the libary

## Design Plan

The stakeholder has tasked the design team to a three-week sprint with the goal
of creating a 3x3 grid of buttons for an Android touchscreen tablet that will
contain various objects. Upon touching either of the buttons, the tablet will
either play a video, play an audio file, or display an image.

The design team consists of three members, each of whom will be delegated
specific tasks, rotating tasks each week.

The three tasks are:

1.  Write the code.
2.  Find videos and images to place in the file directory of the app.
3.  Write documentation.

## This is the working design chart

# ![Flow chart](Flowchart_2.png)

## Summary of Progress

1.  A 3x3 button grid has been created, which can be found in the
    activity_main.xlm
2.  Audio and video files, as well as a link to a YouTube video has been added.
3.  An ActivityMain.kt program has been created which links the buttons in the
    activity_main file to ActivityMain.kt
4.  Documentation within ActivityMain.kt has been written, providing an overview
    of Kotlin and an explanation of how the program works.
5.  The application has been tested on an Android device and works.

## How to Use

1.  Clone the repository: https://github.com/dh2540/Children-sTherapy
2.  Go to file>Open Folder> and choose directory:
    Children-sTherapy/childrensTherapy3
3.  Expand the file manager to the left of the screen on Android Studio and go
    to the directory to open MainActivity.kt:
    childrensTherapy3\\app\\src\\main\\java\\com\\example\\childrenstherapy3\\MainActivity.kt
4.  Open activity_main.xml in Android Studio found in the following directory:
    childrensTherapy3\\app\\src\\main\\res\\layout\\activity_main.xml
5.  Read documentation in MainActivity.kt for an overview of the project.

## Future plans

1.  Button grids should be placed in esilly addable folders. The skeleton code
    for these folders is commented out and documented in MinaActivity.kt
2.  Make multiple button grids to go inside different folders, as before, it
    should be easy to add new ones as the need for more arises
3.  Create more button grids and buttons, each with it's own labling and
    video/audio/image corrasponding to it, so that all created folders have a
    full grid of working buttons

## repository

1.  The repository for this project is
    [Children-sTherapy](https://github.com/dh2540/Children-sTherapy)

## Goals

1.  For the draft pull request: Project should be able to play a video on a single button press and have the outline for adding more grids, folders, and buttons
2.  Final pull request should have 2 grids of working buttons, each within an accesable folder to sort them in-app. All of these should be easy to replicate after the project is finished if the need for more grids/folders/buttons arises
3. Stretch goal: The ability to name the folders, either by a number, color, or some other way to distiinguish them
