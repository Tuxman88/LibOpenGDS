LibOpenGDS
==========

Library to open, read and validate the contents of GDSII files (Graphic Database System II).

This library helps the user to open a file and to load the contents into memory in three main stages:

- Open the GDSII file and validate its contents as bare records. This is useful if someone needs to use some personal conversion from records and other representation. The validations performed are just to check that the record types are correct. but this doesn't validate the organization of the records. The records handled to the user in this stage are basic structures with direct access unions for the information and basic value handling capabilities.
- If asked, using the records loaded, the library can convert them into more sophisticated class instances, representing more abstract components, but still as one instance per record.
- Finally, if asked, the library can convert the previous basic class instances into an advanced representation of the file using various classes to represent the whole file, containing the structures list and the needed calls.

Version
=======

1.0.0 - Still not completed

Tech
====

LibOpenGDS is using some open-source technology solutions to compile and work efficiently.

* [CMake] - Tool used to the compilation of the project.

Compilation
===========

These are the steps needed to get LibOpenGDS ready on your system.

Dependencies
------------

Still designing the library.

Compiling
---------

Still designing the library.

Installation
------------

Still designing the library.

License
=======

GPLv3

[CMake]:http://www.cmake.org/
