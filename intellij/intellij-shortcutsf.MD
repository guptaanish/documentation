##IntelliJ Plugins
1. Save actions
2. Do not use smart tabs and change to tabs
3. Do not add '*' in imports
4. change import order javax.*, nl, java.*, nl, sun.*, nl, org.*,nl, other
5. Builder generator
6. Lombok plugin
7. String Manipulation
8. Maven Helper
9. Grep Console
10. Sonar lint
11. Protobuff support

###Text Selection / Highlight:
	Alt + J / (Shift + Alt + J) --> Highlight next selection
	Ctrl + Alt + Shift + J --> Highlight all occurrences of a text
	Ctrl + W / (Ctrl + Shift + W) --> Select blocks
	F3 / (Shift + F3) --> Find next / previous occurrences

###Code Completions / Insertion:
	Ctrl + J --> Smart insert code 
	Ctrl + Alt + T --> Surround with
	Alt + Insert --> Generate constructor, getter & setters etc
	(dot) .

###Refactoring:
	Ctrl + Shift + Alt + T --> Refactor context window
	
###Extract to variable / constant:
	Ctrl + Alt + V --> to a local variable
 	Ctrl + Alt + C --> Constant
	Ctrl + Alt + M --> Extract selected code to a method
	Ctrl + Alt + P --> Extract selected code and change it to parameter

###Code Navigation:
	Ctrl + B, F4 --> Open selected object / Find usages
	Ctrl + Alt + B --> Find implementations
	Ctrl + P --> View | Parameter Info
	Ctrl + Q --> View | Quick Documentation
	Ctrl + U --> Open base class
	Ctrl + F12 --> Show file structure, methods, constructor etc
	Ctrl + Shift + F7 --> To view all methods of the implemented interfaces in a class, place the caret at the implements keyword in the class declaration
	Ctrl + Shift + F7 --> To view all exit points of a method, place the caret at one of them, for example the return statement
	Ctrl + Shift + F7 --> You can view all statements within the method where certain exceptions can be caught. Place the caret at the throws statement
	Ctrl + H --> To see the inheritance hierarchy for a selected class
	Ctrl + U --> Open base class
	Ctrl + E --> Show recent files
	Ctrl + Shift + E --> Show recent locations
	Alt + F7 --> Find usages

###Debug:
	Alt + F8 --> Evaluate any expression

###Miscellaneous:
	Ctrl + Shift + U --> Change case
	Ctrl + O --> You can easily override methods of the base class
	Ctrl + I --> To implement methods of the interfaces (or of the abstract base class) that the current class implements
	Ctrl + Alt + Up / Down --> To jump between error messages or search results
	Ctrl + Shift + J --> To join two lines into one and remove unnecessary spaces
	Ctrl + Shift + Up / Down --> The Code | Move Statement Up/Down actions are useful for reorganizing code lines, for example for bringing a variable declaration closer to the variable usage.
	F2 / Shift + F2 --> To jump to the next or previous error respectively in the current file.
	F2 / Shift + F2 --> To jump between the highlighted syntax errors.
	Alt + Shift + C --> To quickly review recent changes to the project.
	Alt + Shift + F --> 
	Shift + F1 -->
	Ctrl + Alt + Shift + Insert --> To create a scratch file, then select the language to use.
	Alt + 0 --> Go to messages
	Alt + 1 --> Go to projects
	Alt + 2 --> Go to favorites
	Alt + 3 --> Go to find tab
	Alt + 6 --> Go to TODO
	Alt + 7 --> Go to structure
	Alt + 8 --> Go to services
	Alt + 9 --> Go to version control

###Git Command:
	Ctrl + K --> Commit
	Ctrl + Shift + K --> Rollback
	Ctrl + T --> Git update

###Collapse:
	Ctrl + Numpad (+) --> Expand method
	Ctrl + Numpad (-) --> Collapse method
	Ctrl + Shift + Numpad (+) --> Expand All
	Ctrl + Shift + Numpad (-) --> Collapse All

###Search Commands:
	Shift twice --> Search All Files
	Ctrl + N --> Search class file
	Ctrl + Shift + N --> Search Files
	Ctrl + Shift + A --> Search Actions
	Ctrl + Shift + Alt + N --> Search Symbols

###Settings:
	Ctrl + Alt + S --> Settings
	Ctrl + Shift + Alt + S --> Project Stucture
	
* To scroll a file horizontally, turn the mouse wheel while keeping pressed.
* When you invoke Basic Completion Ctrl+Space, IntelliJ IDEA Community suggests the choices that are reacheable from the current caret position. Press Ctrl+Space again to also see inaccessible classes and members .
* Pressing the same shortcut after you have invoked Smart type completion (Ctrl+Shift+Space) when there's an array of the expected type in the context will suggest getting an element from this array.
* Pressing the same shortcut after you have invoked Smart type completion (Ctrl+Shift+Space) when a collection type is expected will search for arrays with the same component type and suggest converting them using the Attays.asList() call.
* Pressing the same shortcut after you have invoked Smart type completion (Ctrl+Shift+Space) will search for chained expressions of the expected type.
* Pressing the same shortcut after you have invoked Smart type Completion (Ctrl+Shift+Space) when an array type is expected will search for collections with the same component type and suggest converting them using the toArray() call.
* You can view the list of all usages of a class, method or variable across the whole project, and quickly navigate to the selected item. Place the caret at a symbol and press Ctrl+Alt+F7 (Edit | Find | Show Usages).
* Use the Smart code completion Ctrl+Shift+Space after the new keyword to instantiate an object of the expected type.
* When you need to cast an expression value to the required type, use Smart type completion. For example, type
* String s = ( and press Ctrl+Shift+Space to see what happens.
* Smart code completion analyzes the expected type of the whole expression and helps to find methods and variables that are applicable in the current context. It works after the return keyword, in an assignment, in the argument list of a method call, and other places. Press Ctrl+Shift+Space (Code | Completion | SmartType) to get the completion list filtered.
