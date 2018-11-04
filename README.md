# EquationGeneratorJSONClient
Math tutoring program using REST and JSON to generate equations

# Description
EquationGeneratorJSONClient application accepts information about the mathematical question that the user wishes to attempt and the skill lever of the user. A `URL` class and an `InputStreamReader` is used to invoke the EquationGeneratorJSON web service and read the response.  The retrieved JSON is deserialized using FasterXML/jackson-databind 2.9.7. The client application displays the left-hand side of the `Equation` and waits for users to evaluate the expression and enter the result. 

# Getting Started
## Prerequisites
- JDK 1.8
- FasterXML/jackson-databind 2.9.7 - the Java API to serialize the Java Object to JSON (JavaScript Object Notation) format, and de-serialize the JSON string to Java Object.

## Installing
```
git clone git@github.com:lnpeng/EquationGeneratorJSONClient.git
cd EquationGeneratorJSONClient
```
## Running the tests
### Test the EquationGeneratorJSONClient application
- Launch the application
- Select operation
- Choose level
- Generate the Equation
- Answer the math question
- Check answer
- ![Screenshot](https://github.com/lnpeng/EquationGeneratorJSONClient/blob/master/Screen%20Shot%202018-11-04%20at%202.47.12%20PM.png)

# Build
- [Maven](https:maven.apache.org) - Dependency Management.

