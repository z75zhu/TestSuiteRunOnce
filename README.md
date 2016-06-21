# TestSuiteRunOnce

This script can be run on bash to test your program with a test suite file, and it takes in two argument, first one will be a suite file contains a list of stems for your test cases, for example if your suite.txt file's contents looks like this

then you should have test1(2,3).in and test1(2,3).out already in that folder for the script to use
and the second argument takes in the program you are going to test e.g. ./program

for example:
./runSuite suite.txt ./program

if the all the test cases passed it will not return anything.

