# EquationGeneratorJSONClient
Math tutoring program using REST and JSON to generate equations
<div>
<p>EquationGeneratorJSONClient retrieves an Equation object formatted as JSON from EquationGeneratorJSON web service. The client application displays the left-hand side of the Equation and waits for users to evaluate the expression and enter the result.</p>

 <p>A URL class and an InputStreamReader is used to invoke the web service and read the response. The retrieved JSON is deserialized using FasterXML/jackson-databind 2.9.7.</p>
 </div>
