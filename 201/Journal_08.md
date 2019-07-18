# Journal 8
## Function eclarations vs Function Expressions

### Js Interpreter: 
1. First pass: Looks for functions and variables
2. Second pass: looks for executable code


## Functions:<br>
### Declaractions<br>
>function name(a, b){}<br>
>*    gets stored on the first pass<br>
>*    can call this function anywhere

### Expressions<br>
>varsum = function(a,b){}<br>
>*    only the 'var sum' gets stored on the first pass<br>
>*    must call after
<br>
___
## Code Organization
### Top
* *_Global Variables_*
    * Stored at the top, callable by anything at any time during code

* *_Cunstructor Functions_*
    * Stored at the top, and are used with instances

* *_Object Instances_*
    * stored after constructor functions have been formed.

### Middle
* *_Funcction Declarations_*
    * Helper Functions<br>
    * Event handlers <br>

### Bottom
* *_Executable Code_*
    * Stuff that runs on page load
    * Event listeners
    * Function Invoking
___
# Forms
>_"Our Primary form of communicating with the user'_
<br>
___
## Event Listeners
_DOM = Document O Manager_ <br>

    DOMElement.addEventListener('event', function)
    1                   2           3       4

1. Element to listen to
2. Adds on event listener
3. event to listen for
4. function to run when we hear event

## Event Types
* Page Events:
    * load
    * scroll
    * error
* Keyboard events:
    * key up
    * focus
* Mouse events:
    * hover
    * click
    * mouse-up

>### Listener:<br>
> Event listener


___
## Event Bubbling
>### _Events flows outwards, to the least specific parent_

* If an event listener is on the parent, all children can hear it

> Example:<br>
<br>
> If we need to put an event, or cause something to happen to all li's, we can apply the 'something' onto the ul, which will now affect _all_ of the li's, saving us from rewriting code.
> ___

Understand how Event Bubbling works, so you can save yourself work!
___
