# python-asassigment-3
# Python Basic Assignment
## Assignment - 3
---------------
#### 1. Why are functions advantageous to have in your programs?
##### Ans:

Advantages:
1. Increase modularity
2. Increase code reusibility
3. Reduce amount of code
-----------------
#### 2. When does the code in a function run: when it's specified or when it's called?
##### Ans:

The function run(or execute) when it is called. When function is called the control flow which go to first line of code present inside the function.
-----------------
#### 3. What statement creates a function?
##### Ans:

def(keyword) followed by function_name then parentheses.<br>
def function_name():
def function3():
    pass
-----------------
#### 4. What is the difference between a function and a function call?
##### Ans:

- Function: Function is set of codes which produce some result. Function is useless unless it is invoked or called.
- Function Call: Function call is used to invoke or execute set of codes present inside the function.
def function4():        # Function
    return "Inside the function 4"

function4()             # Function call
-----------------
#### 5. How many global scopes are there in a Python program? How many local scopes?
##### Ans:

There are 1 global scopes and 1 local scope in the python program.
-----------------
#### 6. What happens to variables in a local scope when the function call returns?
##### Ans:

The local variables are destroyed when function call returns.
-----------------
#### 7. What is the concept of a return value? Is it possible to have a return value in an expression?
##### Ans:

Return value is value, varible or expression which a function can return.
<br>
Yes function return value can be an expression
def function7(a,b):
    return a+b+10  ## Returning the expression

function7(10, 20)
-----------------
#### 8. If a function does not have a return statement, what is the return value of a call to that function?
##### Ans:

If a function does not have a return statement that means the function is not returning any values.
<br>
In this case after function is executed completly it will return a NoneType.
def function8():
    a = 10
    b = 80
    
type(function8())
-----------------
#### 9. How do you make a function variable refer to the global variable?
##### Ans:

This can be achieved by using global keyword to redefine the variable and make the changes of variable as global change.
var1 = 0
def function9():
    global var1
    var1 = 10
    
print(var1)
function9()
print(var1)
-----------------
#### 10. What is the data type of None?
##### Ans:

None data type is a null variable or null object. The null object is a data type of class NoneType.
-----------------
#### 11. What does the sentence import areallyourpetsnamederic do?
##### Ans:

The statement "import areallyourpetsnamederic" will import the module or package areallyourpetsnamederic.
-----------------
#### 12. If you had a bacon() feature in a spam module, what would you call it after importing spam?
##### Ans:

After import the spam.
<br>
spam.bacon()
# import spam
# spam.bacon()
-----------------
#### 13. What can you do to save a programme from crashing if it encounters an error?
##### Ans:

To save the program from crashing over a runtime error we can use the try and except statement.
<br>
It will save from only the runtime error not the compile time error.
try:
    pass
except:
    pass
-----------------
#### 14. What is the purpose of the try clause? What is the purpose of the except clause?
##### Ans:

- Together try and except block is used to save programme from crashing when an error is encountered.
- Try: Try block is used for any suspicious code which can throw a runtime error.
- Except: Except block is used to catch error if any encountered inside try block.
