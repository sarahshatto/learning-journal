
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