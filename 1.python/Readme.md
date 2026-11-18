Python:
    1.high level, interpreted, general-purpose programming language.
    2. beginner friendly.
    3. ex : print(" hello world!")
    4. python created in netherland by programmer(guido van rossum) in 1980, but releases in 1991.

    5. versions:
    1989 - starting
    1991 - python 0.9.0 first version - functions, exeption, handling, lists, strings.
    2000 - python 2.0 garbage collection, unicode support
    2008 - python 3.0 major update - incompatible with python 2
    2020 - python used only
    2024+ - python 3.12, 3.13 memory efficient version

    6. naming python:
        guido van rossum liked "monthly python's flying circus" british comedy show , so inspire from that he took lang. name as python.

    7. characteristics:
       simple and easy
       open source
       interpreted - line by line execution
       portable - windows, mac, linux
       dynammic typing - no need of datatype
       large library support
       object- oriented
       extensible end embeddable

    8. Areas:
       web developement - django, flask
       data science - numpy, pandas
       AI/ML - tensorflow
       automation/scripting - task automation
       cybersecurity/hacking - ethical hacking tools
       app developement - kivy, beeware
       game development - pygame

    9. working:
        1. run file ex.py
        2. python compiler convert that file into bytecode.
        3. and that bytecode will be stored in .pyc file in __pycache__ folder

        .py -> python compiler -> .pyc(bytecode) -> PVM(python virtual machine) -> machine code(output)

    10. PVM working:
         read bytecode
         instructions execution
         memory manage 
         errors handle 

    11. what if PVM not exist ?
        - need to create different compiler for different OS
        - it was not platform independant
        - momery management, error handling, dynamic typing need to do manually

    12. if you want ot open .pyc file manually:
        - python -m dis hello.py
        - pthon has module - dis(disassembler) - it shows bytecode inside .pyc file in human readable format

        command = python -m dis p.py
