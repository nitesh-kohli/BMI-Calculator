# BMI-Calculator
This is a simple BMI Calculator Project - a basic level project to learn JAVASCRIPT.

# steps to build this project
## in HTML
1.) Create a div element in body.<br/>
2.) Create a form element inside div element.<br/>
3.) Create a P tag inside which create label for height and input field for height.<br/>
4.) Create a P tag inside which create label for weight and input field for weight.<br/>
5.) create a submit button.<br/>
6.) create a empty div tag for the result.<br/>
7.) create a div tag for the weight-guide.<br/>

## in JAVASCRIPT
1.) select form using querySelector from document and hold it in a variable.<br/>
2.) add eventListener to form and the event in this case will be Submit not click.<br/>
3.) in form there is default property to send data to server by post and get method but we don't want that so use preventDefault function on event.<br/>
4.) select height id from document by using .value , now value is in string format so convert into into integer. (same for weight)<br/>
5.) checks for valid height and weight.<br/>
6.) calculate bmi and render it in the result by innerHTML.<br/>
