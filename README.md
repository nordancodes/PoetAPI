# PoetAPI

Web page that will allow users to make calls to the Poet API.

API URL : https://poetrydb.org/ 


API Call Implementation : 

-The POET calls will be consumed using a JQuery Ajax call

-The Ajax() will be called when the 'submit' button is pressed(using .on('click'...)



Page Design : 

-The initial design will be a basic HTML page with 2 input text boxes(1 for Author, 1 for Title).

-There will only be 1 submit button below the 2 text boxes.

-The submit button will be tied to a 'on-click' function.

-If neither field is populated, error will be thrown.

-If only Author is populated, then https://poetrydb.org/author will be used.

-If only Title is populated, then https://poetrydb.org/title will be used.

-If both fields populated, then https://poetrydb.org/author,title/ will be used.

-Any response other than 200 code will throw error using 'error' block of Ajax()




