*******************************************************************************
MIDPS - Medii Interactive de Dezvoltare a Produselor Soft
====
Laboratory work Nr.3 - GUI Programing
----

Virtosu Sava

email: sava.virtosu@gmail.com
*******************************************************************************

### Prerequisites:
  - IDEs: Visual Studio, QTCreator, Code::Blocks
  - Languages: C/C++, C#, Python, Basic,Delphi ...
  - Frameworks: Forms, wxWidgets.
  - Technologies: PyQt.

### Objectives: 
  - Make a simple GUI Calculator  
  - Default operations are: +,-,*,/,power,sqrt,SignInversion(+/-),operation with decimal floating point.
  - Divide your program in two modules - the GUI module and Core Module.
  - Possibility to plot Graphs giving as an argument a function

### General Requirements:
  Laboratory work is considered as successfully passed after fulfilling the following steps:

  1. You must elaborate a Report, in witch you describe your work-flow and the way you are thinking:
    - Laboratory work paper DL is: x.x.x
    - Laboratory work paper must have at least: 4 pages and 2 screen-shots
    - Laboratory work paper must have a conclusion of: 0.5 page
  2. You must elaborate a prototype program, and show how it works during the classes
  3. You must pass the quiz 

### Technical Prerequisites:
  - You must separate your application in two modules:
    - Core module - must include the basic functionality, storing the 
    - GUI module - must include bunch of function that draw the GUI and manage the interaction between GUI elements and the core function
  - Try to make your program cross platform (Windows,Linux,Mac).

### Laboratory Requirements:

  - for _Basic Level_ (grade 5 || 6) you should be able to:
    - Make a simple GUI calculator with basic functions such as +, -, /, *.

  - for _Normal Level_ (grade 7 || 8):
    - Make a simple GUI calculator with basic functions such as +, -, /, *, power, sqrt, SignInversion(+/-). 

  - for _Advanced Level_ (grade 9 || 10) you should be able to:
    - Make a simple GUI calculator with basic functions such as +, -, /, *, power, sqrt and SignInversion(+/-), operation with decimal floating point. 
    - Your program must contain two modules, the GUI module and Business Logic module.

  - for _Geek Level_ (no marks here) explore:
    - Your Business Logic module (the Core module), that represents a bunch of function that	takes some arguments and return the result, must be separated as a library that ca be easily included or accessed in other applications or from the console.
    - Your calculator will be able to plot basic 2D graphs, by giving as an input a function, and obtain as a result a window with drawn graph.
      
      [Here are some Examples](http://s256376672.websitehome.co.uk/KS_3_Year_8/Y8_KS_3_files/Y8_29_30_Graphs/more_graphs.htm)
        
      x + y = 4 
      
      and the [Result](http://s256376672.websitehome.co.uk/KS_3_Year_8/Y8_KS_3_files/Y8_29_30_Graphs/2_graph.jpg)
        
      y = 3x + 1 
      
      and the [Result](http://s256376672.websitehome.co.uk/KS_3_Year_8/Y8_KS_3_files/Y8_29_30_Graphs/1_graph.jpg)


  _Note:_
  _I suggest you to take a look at QTDesigner for constructing GUI, and Python language for Core logic. This Technology binding is named PyQT, and is very interesting imho. If you will make your laboratory work using this technology, take a look at "pyuic" utility. Using this utility you can easily convert your *.ui file in to python code:_
  _"pyuic form1.ui > form1.py"_

### References:
  - [Multitier architecture](http://en.wikipedia.org/wiki/Multitier_architecture)
  - [Different User Interfaces - Same Logic](http://qt-project.org/quarterly/view/different_user_interfaces_same_logic)

### Solved Examples:
Calculator in Visual Studio 2010: 

  - [Link_1](http://www.youtube.com/watch?v=iTVX6O2L3oc)
  - [Link_2](http://www.youtube.com/watch?v=DF2fCWLFSG0)
  - [Link_3](http://www.dreamincode.net/forums/topic/32968-basic-calculator-in-c%23/)

Calculator in Code::Blocks with wxWidgeets: 

  - [Link_1](http://zetcode.com/tutorials/wxwidgetstutorial/layoutmanagement/)
  - [Link_2](http://www.youtube.com/watch?v=PzbMEe6xCPI)

Calculator in QTCreator:

  - [Link_1](http://www.youtube.com/watch?v=Gff6_0-tqUM)
  - [Link_2](http://qt-project.org/doc/qt-4.8/widgets-calculator.html)
  - [Link_3](http://www.developer.nokia.com/Community/Wiki/How_to_make_a_simple_calculator_in_Qt)

Calculator in PyQt:

  - [Link_1](http://zetcode.com/tutorials/pyqt4/layoutmanagement/)
