Doxygen aims to automatically generate documentation for a code project.
Practically speaking, it works by running the CLI command `doxygen`, passing it the configuration file, `Doxyfile`.
This will generate all the expected files assuming no errors occur.
The config file specifies, amoung other things, the following:
- The source code directory
- The output directory for generated documentation files
- What documentation to generate and in what format
- Various metadata 

Most of the work goes into correctly formatting your code and comments.
Doxygen should take care of the rest.
