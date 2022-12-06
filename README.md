# FSH api test 

- Testing Tool: jmeter 5.5

# Deployment
- Make sure you have jmeter installed on your machine.
- Add file `Custom_JsonSchemaAssertion_component-0.4.jar` and `jmeter-plugins-functions-2.1.jar` to `jmeter\lib\ext` directory.
- Copy file `jmeter.properties` to `jmeter\bin` directory.
- Input store test data location path to `User Defined Variables`
```
Ex: Structure of D:\FSH\
├── csv
├── file
├── schema
```
- Input protocal, server/IP, port to `HTTP Request Defaults`
- Input the report file name that you want to get after the test is completed `View Results Tree`
- Press start 


