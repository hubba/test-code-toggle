test-code-toggle
================

Adds a vim script for toggling between tests and code

##Installation

1. Add the script to your plugins folder.

##Usage

The test and code directories are hardcoded in the script and you must change it for your project and needs.
The name of test file must be the same as the name of code file.

test directory - ```test/backend``` - code directory - ```lib/```
test directory - ```test/frontend/spec``` - code directory - ```app/scripts```

1. Open a test file and type ```:OT``` to open the code file.
2. Open a code file and type ```:OT``` to switch back to test file.


