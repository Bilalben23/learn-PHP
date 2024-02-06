# Variable handling functions:
* **falsy values** :
    * [] empty array.
    * "" empty string.
    * 0 
    * "0.0"
    * null
    * false  
* **boolval(var)** : returns the boolean value of a variable.  
---  
* **doubleval(var) / floatval(val)** : returns the float value of a variable.  
---
* **is_countable(var)** : checks whether the contents of a variable is a countable value or not.  
---
* **empty(var)** : checks whether a variable is empty or not.
---
* **get_defined_vars()**: return all defined variables, as an array.  
---
* **gettype(var)** : return the type of a variable.
---
* **intval(var)** : return the integer value of a variable. 
--- 
* **is_array(var)** : checks whether a variable is a array or not.  
---
* **is_bool(var)**: checks whether a variable is a boolean or not. 
--- 
* **is_callable(var)**: checks whether the contents of a variable can be called as a function or not.
---
* **is_integer(var) / is_long(var)**  is alias of **is_int(var)**: checks whether a variable is of type integer or not.
---   
* **is_double(var)** is alias of **is_float(var)**: checks whether a variable is of type float or not 
---
* **is_iterable(var)** : checks whether the contents of a variable are iterable value or not. 
---
* **is_null(var)** : checks whether a variable is NULL or not.
---
* **is_numeric(var)** : checks whether a variable is a number or a numeric string.
---
* **is_resource(var)**
---
* **is_string(var)**
---
* **is_scalar(var)**  
---
* **is_object(var)**
---
* **isset(var...)**: checks whether a variable is set, which means that it has to be declared and is not NULL.
---
* **print_r(var)** : prints the information about a variable in a more human-readable way.
---
* **serialize** : converts a storable representation of a value.
---
* **settype(var, "type")** :  converts a variable to a specific type.
---
* **strval(var)** : returns the string value of a variable.  
---
* **unserialize()** : converts serialized data back into actual data.
---
* **unset(var,...)** : unset a variable.
---
* **var-dump()**:dumps information about a variable one ore more. (type, value).
* **var_export()** :  outputs or returns structured information about a variable. 