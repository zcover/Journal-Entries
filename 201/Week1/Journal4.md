# Journal 4

## Truthy/Falsey


Using two ='s makes things "truthy", or basically true<br>
     
        '2' == 2
        >true

## True/False
>Using 3 ='s makes things True, and if it is not true, it will be false.

        '2' === 2
        >false
---
___
# Functions
___
## Functions are like a sandwich
1. Name the funcion<br> 
2. tell it what it does<br> 
3. invoke it<br>
Observe:

        function name(){
            consolelog('says a thing')
        }
        >does nothing

        //to invoke the function, call it
        name()
        >says a thing
### Functions do code

    var userAnswer = 'yes';
    
    if(userAnswer === 'yes'){
        console.log('The user Entered yes')
    }
    >The user Entered yes

### Now sandwich it:

    var userAnswer = 'yes';

    function doSomething(){
        if(userAnswer === 'yes'){
            console.log('The user Enterd yes')
        }
    }

    doSomething()

    >The user Entered yes

Notice that the code within our function brackets stays exactly the same. At the bottom, we have _invoked_ the code within the function, by calling the function using _functionname()_.

* You can use a _return_ command to call information.<br>
<br>
___
## Function rules: Variables
___
    function sayHi(){
    var userName = 'Bob';
    }
    console.log userName
    >[insert lots and lots of error text yadadadaa filler text this will go on for eeeverrrr]

### - Scope:
- Variables created within a function are only _scoped_ to that function.
### - Global Variables:
- Variables that exist in the _entire_ code base, written outside of any function.
### - Parameter:
- Something the function takes in.
<br>

        function doSomething(name){
            console.log('Hello' + name)
        }

        console.log(doSomething)
        >Hello undefined

_Note: Name has not been defined_

    function doSomething(name='bob'){
        console.log('Hello' + name);
    }

    doSomething('joe');
    doSoemething('Jon');
    doSomething'Corey');
    doSomething();

    >joe
    >Jon
    >Corey
    >bob 
    //since bob is the default value given to name in our function

### - Argument:
- The actual thing that we feed into a function to invoke it.

___
## Challenge:
* ### Write a function that takes in three parameters
* ### Returns a sentence about all three
---
# Github Forking
## _The process of sharing git files through github_

* ## User [A] creates repo
* ## Another user [B] (anyone) _forks_ the repo
* ## User B clones the repo to drive.<br>
    ### User B is now _driving_ the repo on _their_ local machine
* ## User B edits and A-C-P to **his/her** Github
* ## User B makes a _pull request_
* ## User A decides whether or not to accept or deny the commit changes to the head file
****************
### *If paired programming, there is a _driver_ and a _navigator_. The Navigator is the one deciding all of the changes/development of whatever it is that is being worked on, while the driver is the one actually writing the code.
___