### Read Reflection 08

## JavaScript and Jquery book notes

#### Comparison and Logical Operators pg 150-151, 156-157
- You can evaluate a situation by comparing one value in the script to what you expect it might be. The result will be a Boolean: true/false result.

            ==  
        IS EQUAL TO 

- compares two values to see if they're the same. 
- Examples: 
  - 'Hello' == 'Goodbye' would result in FALSE
  - 'Hello == Hello would result TRUE 

            ===
        STRICT IS EQUAL TO 

- compares two values to see if they're the same *data and type* and the value is the same. 
- Examples: 
  - '3' === 3 would result in FALSE
  - '3' === '3'  would result TRUE 

            !=
        IS NOT EQUAL TO 

- compares two values (numbers/strings/booleans) to see if they are not the same. 
- Examples: 
  - 'Hello' != 'Goodbye' would result in TRUE
  - '3' === '3'  would result FALSE 

            !==
        STRICT NOT EQUAL TO 

- compares two values (numbers/strings/booleans) to see if the data and values are not the same.
- Examples: 
  - '3' !== 3 would result in TRUE
 
            >
        GREATER THAN 

- compares two values. 
 
            >
        LESS THAN 

- compares two values. 

            >= 
        GREATER THAN OR EQUAL TO

- compares two values. 

            <= 
        LESS THAN OR EQUAL TO

- compares two values. 

            && 
        LOGICAL "AND"

- Tests more than one condition. 
  - See below example.

           || 
        LOGICAL "OR"

- Tests at least one condition. 
  - If either result returns true, the result is true. 

            ! 
        LOGICAL "NOT"

- Takes a single Boolean value and inverts the result. 
- !(2<1) is TRUE. 



#### LOCAL OPERATORS, page 156-157 
- Comparison Operators usually return single values of True/False. 
- They allow you to compare the results of more than one comparison. 

Example: 

  - ( (5<2) && (2>=3))
  
  Expression 1 (5 < 2) is False. 

  Expression 2 (2 >= 3) is False. 

  This expression would result in FALSE. 

#### LOOPING, page 170-173, 176 

Example: 

    (var *i* = 0; *i* < 10; i++) { <br>
        document.write(*i*)
  }


- First time the loop is run, the variable *i* (the counter) is assigned a value of 0. 
- Every time the loop is run, the condition is checked for a TRUE/FALSE result. (Is the value less than 10?) 
- If the condition still gives a TRUE result, then the code inside the loop (code block/curly brackets) is run again. 
- The variable *i* can be used inside the loop. When the statement has finished, the variable is incremented by 1. ( represented in the above equation as i++)
- When the statement no longer results in TRUE, the loop stops. 



