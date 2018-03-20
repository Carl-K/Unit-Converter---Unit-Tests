# Unit-Converter---Unit-Tests
The units tests I have created for my Objective-C app Unit Converter

The files in the Interfaces folder are the files relevant to the unit tests found in the Unit-Tests folder.  The DoubleFunctions interface has 2 methods to appropriately compare floats which is used in the unit tests.  The -----System interfaces are singletons so I had to init them a bit differently in the unit tests as opposed to the standard setup and teardown methods.

LengthTests has a test function for each type of exlipcit length conversion while the rest of the unit tests uses test functions that loop through each type of conversion per length unit.  They do the same thing but the file is shorter.  All of the unit tests test both valid and invalid unit inputs.
