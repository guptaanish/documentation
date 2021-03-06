##IntelliJ Plugins
1. Save actions
    (Add only those file extension which you need to be auto formatted when saved)
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
    Ctrl + Alt + F --> Extract to a field
	Ctrl + Alt + V --> Extract to a local variable
	Ctrl + Alt + P --> Extract to a parameter
 	Ctrl + Alt + C --> Extract to a constant (public static ....)
	Ctrl + Alt + M --> Extract selected code to a method
    Ctrl + Alt + N --> Inline
    Ctrl + F6 --> Change signature
    Alt + Delete --> Safe Delete 
    Shift + F6 --> Rename
    F5 --> Copy
    F6 --> Move
    
###Code Navigation:
    Ctrl + A --> Select All
	Ctrl + B, F4 --> Open selected object / Find usages
	Ctrl + C --> Copy
	Ctrl + D --> Delete line
	Ctrl + E --> Show recent files
	Ctrl + F --> Find
	Ctrl + G --> Go to line
	Ctrl + H --> To see the inheritance hierarchy for a selected class
	Ctrl + I --> To implement methods of the interfaces (or of the abstract base class) that the current class implements
	Ctrl + J --> Smart insert code 
	Ctrl + K --> Git push
	Ctrl + L --> Find (Works same as Ctrl + F)
	Ctrl + M --> Move the cursor to center 
	Ctrl + N --> Search class file
	Ctrl + O --> You can easily override methods of the base class
	Ctrl + P --> View | Parameter Info
	Ctrl + Q --> View | Quick Documentation
 	Ctrl + R --> Search and replace
 	Ctrl + S --> Save
 	Ctrl + T --> Git update
	Ctrl + U --> Open base class
	Ctrl + V --> Paste
	Ctrl + W / (Ctrl + Shift + W) --> Select blocks
	Ctrl + X --> Cut
	Ctrl + Y --> Delete line
	Ctrl + Z --> Undo
	Ctrl + Alt + B --> Find implementations
	Ctrl + F12 --> Show file structure, methods, constructor etc
	Ctrl + Shift + F7 --> To view all methods of the implemented interfaces in a class, place the caret at the implements keyword in the class declaration
	Ctrl + Shift + F7 --> To view all exit points of a method, place the caret at one of them, for example the return statement
	Ctrl + Shift + F7 --> You can view all statements within the method where certain exceptions can be caught. Place the caret at the throws statement
	Ctrl + Shift + F12 --> Toggle maximizing editor
	Ctrl + Shift + E --> Show recent locations
	Ctrl + Shift + ] / [ --> Select till code block end / start
    Ctrl + Shift + H --> Method hierarchy
    Ctrl + Alt + H --> Call hierarchy
    Ctrl + Shift + F7 --> Highlight usages in file
    Ctrl + Alt + F7 --> Show usages in a popup window
    Ctrl + F7 --> Find usages in current file
	Alt + F7 --> Find usages in all files
	Ctrl + ` 

###Compile and Run:
    Ctrl + F9 --> Make project
    Ctrl + Shift + F9 --> Compile selected file, package or module
    Alt + Shift + F9 --> Select configuration and debug
    Alt + Shift + F10 --> Select configuration and run 
    Shift + F10 --> Run
    Shift + F9 --> Debug
    Ctrl + Shift + F10 --> Run context configuration from editor

###Debug:
	Alt + F8 --> Evaluate any expression

###Miscellaneous:
	Ctrl + Shift + U --> Change case
	Ctrl + Shift + V --> Paste from history
	Ctrl + Alt + Up / Down --> To jump between error messages or search results
	Ctrl + Shift + J --> To join two lines into one and remove unnecessary spaces
	Ctrl + Shift + Up / Down --> The Code | Move Statement Up/Down actions are useful for reorganizing code lines, for example for bringing a variable declaration closer to the variable usage.
	F2 / Shift + F2 --> To jump to the next or previous error respectively in the current file.
	F2 / Shift + F2 --> To jump between the highlighted syntax errors.
	Alt + Shift + C --> To quickly review recent changes to the project.
	Alt + Shift + F --> Bookmarks
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
	Ctrl + T --> Git update
	Ctrl + K --> Commit
	Ctrl + Shift + K --> Push
	Ctrl + Shift + ` --> Opens Git Branches popup
	Alt + ` --> VCS quick popup

###Collapse:
	Ctrl + Numpad (+) --> Expand method
	Ctrl + Numpad (-) --> Collapse method
	Ctrl + Shift + Numpad (+) --> Expand All
	Ctrl + Shift + Numpad (-) --> Collapse All

###Search Commands:
	Ctrl + N --> Search class file
    Shift twice --> Search All Files
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
