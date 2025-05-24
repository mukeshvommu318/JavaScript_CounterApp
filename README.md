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

    -> JavaScript Functions
	-> Function Expression : 
		1st -> Declare a variable
		2nd -> Assign a function to that variable
		3rd -> Call the Function using variable name
		Ex: 
		const greet = function(name) {
  			return "Hello, " + name + "!";
		};
		console.log(greet("Mukesh"));               // Output: Hello, Mukesh!
  
	-> Function Declaration :(Normal function)
		function greet(name) {
 	 		return "Hello, " + name + "!";
		}
		console.log(greet("Mukesh"));  // Output: Hello, Mukesh!

	-> Data Structures
 		JavaScript 
		-> Array holds an ordered sequence of items
		-> Array creation :  let myArray = [1,"two",3,3.5]
		-> Accessing the elements ( console.log(myArray[0]) )
		-> Modifyin the Array ( myArray[1] = 1 )   
		-> Finding the Array Length : ( myArray.length )		
		-> Adding the element into array : ( myArray.push(5) )         // [1,"two",3,3.5,5]
		-> Remove the element from array : ( myArray.pop() )           // [1,"two",3,3.5]


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

    -> Python Functions
	-> Normal Function 
		def greet(name):
    	     	     return f"Hello, {name}!"
		message = greet("Mukesh")
		print(message)                    # Output: Hello, Mukesh!

    -> DataStructures in python
    	Python
	-> List holds an ordered sequence of items
	-> List creation : my_list = [1, 2, 3, 4, 5]
	-> Accessingg the List ( print(my_list[0]) )
	-> Modifyoing the List ( my_list[1] = 25 )
	-> Finding the Array length : ( len(my_list) )
	-> Add element in List : 
		1) Append() : adds one item at the end
			my_list.append(4)
		2) insert() : adds Item at specific index
			my_list.insert(1, 10)        // Insert 10 at index 1
		3) extend() : Adds multiple items
			my_list.extend([5, 6])
	-> Remove the element in List :
		1) pop(index) : It removes elemnt at specific index
			removed = my_list.pop(1)
		2) remove(value) – Removes the first occurrence of a value
			my_list.remove(20)
		3) clear() – Removes all elements
			my_list.clear()
## **DOM**
	-> How to Create HTML element using JavaScript
		Ex :
		let h1Element = document.createElement("h1");        // 1. Create a new element
		h1Element.textContent= "WebTechnologies"             // 2. Set text content
		console.log(h1Element) // <h1>WebTechnoligges</h1>
		document.body.appendChild(h1Element)		     // 3. Append to body

		let containerElement = document.getElementById("my_container")
		containerElement.appendChild(h1Element)              // 4. Appending the element to specific container(div)


	-> Adding the event Listener Dynamically
	
		let btnElement = document.createElement("button")
		btnElement.textContent = "Clickme";
		btnElement.onClick = function(){
			console.log("click event is clicked")
		}
		document.getElementById("my_container").appendChild(btnElement);

	-> Add class attribute to element ( <h1 class="heading">head</h1> )
		h1Element.classList.add("heading");
	
	-> Remove the class attribute
		h1Element.classList.remove("heading");


