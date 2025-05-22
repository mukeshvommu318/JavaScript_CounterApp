# Counter App
![countapp](https://github.com/mukeshvommu318/JavaScript_CounterApp/blob/df8223f841e408ab7c07e1b6abb31898677b2b00/Screenshot%20(6).png)

**Live link :** https://mukeshvommu318.github.io/JavaScript_CounterApp/

**The Counter App is a simple project designed to help beginners understand and practice key concepts in HTML, CSS, and JavaScript.**

## Learnings
**-> Dom Manipulations**
- Understanded how to access and manipulate the HTML elements using (textContent, style, getElementById() )

**-> Strength the Javascript Basics**
- DataTypes
- Variables
- Conditional Statements
- parseInt()
- typeof() operator

**-> Difference between the JavaScript and Python**
    
    **Java script**
    ->number - 10, 9.567
    ->Boolen - true, false (starts with samll letter)
    ->String - enclosed with ( "_", '_', `_`(backticks) )
    ->Undefined -
	    reasons : 1) Variable is declared but not assigned value
		            2) Accessing non-existent object property
			              Ex: const user = { name: "Kiran" };
                			    console.log(user.age); // undefined (no 'age' property)
		            3) Function with no return statement
			              Ex : function greet() {
  				                  console.log("Hello");
			                   }
			                   let result = greet(); // Hello
                         console.log(result);  // undefined (no return value)
		          4) Function parameter not passed
              			Ex: function sayHello(name) {
  				                console.log("Hello " + name);
			                  }
			                sayHello(); // Hello undefined
		       5) Array element not initialized
			              Ex: let arr = [1, , 3];
			                  console.log(arr[1]); // undefined

    -> parseInt("") : Convert the String to Integer 
		    Ex: parseInt("20") -> typeof(20) -> number

    -> typeof() operator

    -> Conditional Statements  (uses {} ; else if)
	          let num = 10;
	          if (num > 0) {
    	          console.log("Positive");
          	} else if (num === 0) {
    	          console.log("Zero");
	          } else {
                console.log("Negative");
	          }

    -> Ternary operator
	        (condition ? True_Value : False_Value)
	        let result = (num > 0) ? "Positive" : "Negative";



    **Python**
    ->Integer type - 10
    -> float type - 9.676
    -> Boolean type - True, False (starts with capital letter)
    -> String - enclosed with ( '_', "_", '''_'''/ """_""" (Multi Line String) )

    -> int("")  : Ex : int(float("12.34")) -> Sring to Float to Int -> type(1234) -> Integer

    -> type() operator 

    -> Conditional Statements  (indentation(:) elif)
	        num = 10
	        if num > 0:
    	        print("Positive")
	        elif num == 0:
    	        print("Zero")
	        else:
              print("Negative")

    -> Ternary operator (single line if-else)
	        ( a if condition else b )
	        result = "Positive" if num > 0 else "Negative"
