Download Link: https://assignmentchef.com/product/solved-csi121-lab4-java-exception-handling-process
<br>
<ul>

 <li>Familiar with Java exception handling process.</li>

</ul>

<strong>Tasks</strong>

In Assignment 1, the user was required to input some personal information to initialise the course enrolment process and select the major and elective subjects to complete the enrolment. However, the requirement of A1 (please check Moodle for A1’s requirement and solution) does not consider the exception handling. It is possible that the user inputs invalid information during the enrolment process. In this task, you are asked to design and implement the exception handling solutions on top of A1’s solution (you can use your own solution or the solution provided by me). Please carefully consider the possible invalid information the user may input during the enrolment process, and design and implement relevant solutions to handle those possible exceptions.




It is required that the updated program shall be robust to any possible inputs provided by the user and shall not have the runtime error. The exception handling process can detect the user’s invalid inputs and provide the chance to allow the user to re-input the information until it is valid. The possible (but not limited) invalid inputs could be:




<ol>

 <li>No inputs (the user just press the Return button);</li>

 <li>Invalid DOB format (correct format shall be dd/mm/yyyy. All other formats such as dd-mm-yyyy, mm,dd, yyyy and ect are invalid);</li>

 <li>Invalid DOB (the date does not exist, such as 29/02/1999, 31/04/2000, and etc);</li>

 <li>Invalid major index (input 0 or 6 for BCS major selection);</li>

 <li>Invalid elective subject code (input not existing subject code such as CSIT191), and</li>

 <li>Others (optional, you can do other validation checking based on your own assumptions)</li>

</ol>




You may need to modify A1’s solution (fields and methods) to complete this task based on the following requirements.




<ul>

 <li>You can use the build-in exceptions predefined by Java (Exception and/or sub-class of Exception). However, your program must contain at least one custom exception defined by yourself via extending the Exception class.</li>

 <li>For each exception handling, you may use the “throw”, “try…catch”， “finally” and “Assertion” blocks.</li>

 <li>Your program must contain at least one multiple “catch” blocks.</li>

 <li>Your program must contain at least one “finally” block.</li>

 <li>Your program must contain at least one “Assertion” block. (note: assertions are not enabled by default. In order to execute the programs contain assertion, you shall run your program as</li>

</ul>

“java -ea ClassName”.

<ul>

 <li>Please test the updated program with some possible invalid inputs listed above (Items 1~5 are essential, and Item 6 is optional).</li>

</ul>