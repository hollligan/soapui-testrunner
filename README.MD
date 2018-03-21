# This is soapUI test runner (CLI) with docker container

## Example:
` docker run --rm -it \ 
   -v ./example-soapui-project.xml:/tmp/soapui-project.xml
   hollligan/soapui-testrunner \
   -s "TestSuite 1" `
   
### or
` docker run --rm -it hollligan/soapui-testrunner \
    -s "TestSuite 1" 1> /dev/null; \
    echo $? `

## help:
` docker run --rm -it hollligan/soapui-testrunner `
