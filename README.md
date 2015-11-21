# JBehaveStack
Stack example implemented with JBehave using eclipse IDE


This example starts from the tutorial https://blog.codecentric.de/en/2011/03/automated-acceptance-testing-using-jbehave/


The project can then be build issuing the following command:

mvn compile

The required style-files for the reporting can be downloaded using this command (required only once):

mvn generate-resources

Afterwards the tests can be executed using this command:

mvn integration-test

All commands must be executed from the project directory that is also containing the pom.xml-file.
