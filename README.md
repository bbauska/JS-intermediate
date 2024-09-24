# JS-Intermediate-JS
JavaScript - intermediate (vanilla and more). Using sublime text.
Because you cannot have parentheses after the function names in event handlers or listeners, passing arguments requires a workaround.
Usually, when a function needs some information to do its job, you pass arguments within the parentheses that follow the
function name. When the interpreter sees the parentheses after a function call, it runs the code straight away. 

In an event handler, you want it to wait until the event triggers it. Therefore, if you need to pass arguments to a function that is
called by an event handler or listener, you wrap the function call in an anonymous function. 
Event name
Start of anonymous function
The named function.-Li includes parentheses 
el .add Event Listener(' blur' , function()

The anonymous function is used containing the -- chec kUsername ( 5) ;
parameter after the } f l ), a se ;
function name.
I ~nd of statement 
End of addEventl i stener() method 
Event flow Boolean (see p260)
End of anonymous function
The named function that requires the arguments lives inside the anonymous function.
8 EVENTS
Although the anonymous function has parentheses, it only runs when the evenUs triggered.
as the second argument. It "wraps around" the named function.
The named function can use arguments as it only runs if the anonymous function is called.
