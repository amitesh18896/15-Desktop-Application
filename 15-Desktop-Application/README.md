# 15 Desktop Application

A collection of 15 small — *minute* — desktop applications written in Python
using the PyQt framework. These apps are intended as examples from
which you can poke, hack and prod your way to writing your own tools.

> Many of these apps have more detailed write-ups on my PyQt5/PySide2 

## The apps

The apps showcase various parts of the Qt framework, including advanced widgets,
multimedia, graphics views and decorationless windows. However, the most
generally interesting/feature complete applications are Minesweeper, Solitaire
and Paint.

1. [Web Browser (untabbed)](browser/) - "MooseAche"
1. [Web Browser (tabbed)](browser_tabbed/) - "Mozzarella Ashbadger"
1. **[Minesweeper](minesweeper/) - "Moonsweeper"**
1. [Notepad](notepad/) - "No2Pads"
1. [Calculator](calculator/) - "Calculon" (QtDesigner)
1. [Word Processor](wordprocessor/) - "Megasolid Idiom"
1. [Webcam/Snapshot](camera/) - "NSAViewer"
1. [Media Player](mediaplayer/) - "Failamp"
1. [Post-it Notes](notes/) - "Brown Note" (QtDesigner)
1. **[Paint](paint/) - "Piecasso" (QtDesigner)**
1. [Unzip](unzip/) - "7Pez" (QtDesigner)
1. [Translator](translate/) - "Translataarrr" (QtDesigner)
1. [Weather](weather/) - "Raindar" (QtDesigner)
1. [Currency converter](currency/) - "Doughnut" (PyQtGraph)
1. **[Solitaire](solitaire/) - "Ronery" (QGraphicsScene)**

## Getting started

To use each app you first need to install the requirements. In most cases
the only requirements are PyQt5, and occasionally requests. To install
app-specific requirements change to the folder of the app and run:

    pip3 install -r requirements.txt
    
Once the requirements are installed, you can run the app using Python 3.

    python3 <filename>.py
 
The application window should appear.

## Want to build your own apps?


## License

All code is **licensed under an MIT license**. This allows you to re-use the code freely,
remixed in both commercial and non-commercial projects. The only requirement is to
include the same license when distributing.

Thanks

Created By Amitesh Kumar Mishra...