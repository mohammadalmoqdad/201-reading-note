## CH 10
* **execution contexts**:
  1. GLOBAL CONTEXT: everything inside the js code and outside any function.
  2. FUNCTION CONTEXT: The code strats running within the function.
  3. EVAL CONTEXT: Text is executed like code in an internal function called eva l {) 
* **VARIABLE SCOPE**: 
  1. GLOBAL SCOPE : a variable is declared outside a function..
  2. FUNCTION-LEVEL SCOPE: When a variable is declared within a function, it can only be used within that function.
* Each time a script enters a new execution context, there are two phases of activity: 
  1. PREPARE:
    * The new scope is created .
    * Variables, functions, and arguments are created 
    * The value of the this keyword is determined 
  2. EXECUTE:
    * Now it can assign values to variables.
    * Reference functions and run their code .
    * Execute statements.
* If a JavaScript statement generates an error, then it throws an exception.At that point, the interpreter stops and looks for exception-handl ing code. 
* ***ERROR OBJECTS***:
  1. Syntax Error : syntax id not corret
  2. ReferenceError:variable that is not declared or is out of scope.
  3. EvalError : iNCORRECT USE OF eval() FUNCTION.
  4. URI Error: INCORRECT USE OF URI FUNCTIONS 
  5. Type Error: VALUE IS UNEXPECTED DATA TYPE.
  6. RangeError: NUMBER OUTSIDE OF RANGE 
  7. Error : GENERIC ERROR OBJECT .
  8. NaN: NOT AN ERROR 
* The error can be handleited gracefully using the try catch, finally statements.Use them to give your users helpful feedback. 

