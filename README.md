AirBnB_clone

My BnB Description 🏷️

HBNB is a complete web application, integrating database storage, HTML/CSS templating, API, front-end and others.

This group or team work is part of the ALX School Software Engineering program.
It represents the first step towards building a full web application: the AirBnB clone.

This first step consists of:

• a custom command-line interface for data management,

• and the base classes for the storage of this data.

The Command Description And How To Use Them ���

The console works both in interactive mode and non-interactive mode, much like a Unix shell. It prints a prompt (hbnb) and waits for the user for input.

CommandExampleRun the console./console.pyQuit the console(hbnb) quitDisplay the help for a command(hbnb) help <command>Create an object (prints its id)(hbnb) create <class>Show an object(hbnb) show <class> <id> or (hbnb) <class>.show(<id>)Destroy an object(hbnb) destroy <class> <id> or (hbnb) <class>.destroy(<id>)Show all objects, or all instances of a class(hbnb) all or (hbnb) all <class>Update an attribute of an object(hbnb) update <class> <id> <attribute name> "<attribute value>" or (hbnb) <class>.update(<id>, <attribute name>, "<attribute value>")

Interactive mode (example)

$ ./console.py (hbnb) help Documented commands (type help <topic>): ======================================== EOF help quit (hbnb) (hbnb) (hbnb) quit $

Non-interactive mode (example)

$ echo "help" | ./console.py (hbnb) Documented commands (type help <topic>): ======================================== EOF help quit (hbnb) $ $ cat test_help help $ $ cat test_help | ./console.py (hbnb) Documented commands (type help <topic>): ======================================== EOF help quit (hbnb) $

Testing 📏

Unittests for the HolbertonBnB project are defined in the [tests] To run the entire test suite simultaneously, execute the following command:

$ python3 unittest -m discover tests 

Alternatively, you can specify a single test file to run at a time:

$ python3 unittest -m tests/test_console











