
# ReadReflection 06 

## Javascript & JQuery Book, Jon Duckett

### Covering: 
- Variables
- 

- Javascript is Case Sensitive. HourNow/hourNow/Hournow all reference different things. 

-Statements are instructions- each starts on a new line and ends with a semi-colon. 

-Comments are encouraged to explain what your code does for better collaboration and clarity. Ex: / * This is what my script does... * / 
  - Multi line comments use the /*  and */ marks, single line comments only need to begin with two /'s. 


### Variables

- Scripts utilize variables to temporarily define and store data in order to perform the code written. 
  - Data stored in a variable can change each time the code is run.
  
  Ex: Var quantity; <br>
        quantity = 3

  - "var" (or variable) represents what programmers would call a "keyword"
  - in order to use the keyword, you need to give it a name or identifier. in this example above, "quantity" is the identifier.
  - Once you have created a variable, you can tell it what info you want it to store, aka assign a value to it. (In this example, quantity =3)
  - after defining a variable (ex. var quantity;) you can then use the variable by its name. When possible a variable's name should describe the kind of info the variable holds.
  - "=" is an assignment operator and is used to assign value to the variable. 
    - Until the value has been assigned, you refer to this variable as undefined. 


- DATA TYPES, pg. 62
  - Javascript distinguishes between numbers, strings and true or false values, AKA Booleans. 
    - Numeric Data type: 
      - used for tasks that involve counting, calculating, etc...
      - you use numbers 0-9. No commas, but you can have negative numbers.
      - Ex: 0.75

    - String Data Type: 
      - consists of letters and other characters. 
      - always within a pair of quotes. You can use double quotes or single quotes, but they have to match one another. 
      -Ex. 'Hi, Ivy!'

    - Boolean data type
      - can have one of two answers: true or false. 
      - like a light switch- either on or off.
      - Ex. true / false

-Numbers can also be used for tasks like moving an element on a page or determining the size of a screen

## Using a variable to store a number

- Define the variables to be used 

Ex: 

Var price; 
Var quantity; 
Var total; 

- Assign value to the defined variables

price = 5; 
quantity = 14; 
total = price * quantity; 

-Another way to define variables is to define a variable based off of corresponding HTML that is linked. 

Ex: <br>

var el=document.getElementById('cost');
el.textContent = '$' + total; 

- This first line of code looks for an element in the html with the Id of 'cost' identified and defines the "el" variable with whatever was identified.

- The second line takes that "el" variable and replaces with the identified value, and uses the value in the equation listed.

## Using a variable to store a boolean

- boolean variables can only have a value of true/false. 
- can be correlated with CSS rules that indicate a visual representation for true/false value 

- popular use: When the value can only be true/false, or 1/0
- another popular use is to use boolean variables in paths, where the true/false result will send people into different paths. 

## Shorthand for defining variables:
- Examples on Page 67

- You can change the values of a variable within the same script.
  - No need to use the var ____ line, you can just take the existing value and use an = to equate it to something else. 

  ## Rules for naming variables:

1. Name must begin with a letter, $, or _. Cannot be a number. 
1. No dashes or periods
1. Cannot use keywords or reserved words.
1. Case sensitive.
1. Use a name that indicates what kind of data the variable will be storing. 
1. Use CamelCase. Ex: FirstName, LastName

