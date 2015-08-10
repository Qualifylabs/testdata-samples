
Qualify Test Data: samples
==================================
In this repository you will find execution file samples for Qualify executor. 

Robot framework
----------------

Test data is required to have an rf argument file in the main folder.

Example *arguments.txt* content is like following:

    --doc This is an example (where "special characters" are ok!)
    --metadata X:Value with spaces
    --variable VAR:Hello, world!
    # This is a comment
    path/to/my/tests

File is required to be in *.zip* format which contains everything that is required by tests.

Template is under [``robotframework``](https://github.com/Qualifylabs/testdata-samples/tree/master/robotframework)

