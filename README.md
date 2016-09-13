# {{ cookiecutter.project_name }}

TODO:  This isn't finished... I need to copy over a C++ project template here (from cookiecutter ideally) and add in wiring pi and have it do a blink light and also post the Wiring diagram and schematic.  

{{ cookiecutter.project_short_description}}

## Building From Source

First make sure that you have [CMake](http://www.cmake.org/) and an C++ compiler environment installed.

Then open a terminal, go to the source directory and type the following commands:

    $ mkdir build
    $ cd build
    $ cmake ..
    $ make

## Running unit tests

After building this project you may run its unit tests by using these commands:

    $ make test  # To run all tests via CTest
    $ make catch # Run all tests directly, showing more details to you


