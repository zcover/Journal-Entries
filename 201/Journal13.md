# Class 13
## Final Exam
The Final is due Sunday at 11:59 PM, you will only get **one** retake.
<br>
The test will likely take an hour or so.. Take as much time you need to study, but make sure your final submission is in by Sunday Night.
<br>
### The test is open book, notes, etc. but NOT open peer. Do not ask for help.
___
Vocab:<br>
* Ternary
# Persistance
How we store our data

databases hold data
# Local Storage
- Data stored in your file systems
- Native to JS
- **JSON**
    - Java
    - Script
    - Object
    - Notation
### Setters and getters
- set items 
    - (key, data)
        - key is a string
        - data must be a string<br>
- get items
    - (key)
        - key is the string previously turned into a string<br>
### Browser Local Storage
- To view your browser's local storage, click on >> to view more options
    - Click on Application
- localStorage.clear( );
    - make sure you invoke  ( ) *

### * Important! * After going through local storage, the Instanciated objects are no longer instanciated, and therefore cannot use any prototypes of the constructor function.

## BusMall
- Can use local Storage to save total values.
- Create a new branch "local-storage"
- Make total votes stay in local storage if leaving page or closing browser.
- Assignment is left vague for you to create and utilize local storage as you see fit.

### Questions:
1. When do we store data?
    >When user is done.
2. When do we retrieve data?
    >When user loads page.<br>

If we retrieve the data on page load, then the items' vote values will be greater than 0.
___
___

# Goals:
Goal for the assignment is to take in user's vote selections, and store those responses to local storage.

User should still bel imited to 25 questions.

User will be held to 25 votes upon returning to the web page

25-x , where x is the previous number of votes.