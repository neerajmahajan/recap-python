# recap-python
Repository to revise and document Python laguage.

### Variables
  * x =10
  * y =20
  * single_quote_string = 'my string'
  * double_quote_string = "other string"
  * single_quote_string[0] will return m
  * strings are sequence of letters
  
### Methods
  * Method is created with def keyword
  * method signature end with : 
  * methods instructions should be indented
  
  ```
   def print_method():
       print("Hello")
       print("World")
   def multiply(arg1, arg2):
       return arg1 * arg2
  
  ```
  
### Collections
  * list : ordered collections of elements. 
  ``` list_grades = [1,2,3,4,5,6] ```
  ``` list_grades.append(7) ```
  ``` list_grades[0] = 11 ```
  * tuples : similar to list but immutable.
  ``` tuple_grades = (1,2,3,4,5,6) ```
  ``` new_tuple = (1,)
      tuple_another = 1,
      more_tuple_ex = (1,2,3)  
  ```
  * sets : unordered, unique collection of elements.
  ``` set_grades = {1,2,33,33,4,5} ```
  ``` set_grades.add(10) ```
  ``` intersection ```
  ``` union ```
  ``` difference ```
### module
* https://realpython.com/python-modules-packages/
* module is just a python file, which can have variables,function,classes or print statements
* a module can be executed as a script or can be imported in another module using __import__ statement.
*  ``` python module_name.py ``` will execute the code inside the module and when a module is executed as a script, the __name__ variable is set a value of __main__ eg below
```
if (__name__ == '__main__'):
    print('Executing as standalone script')
```    
    
