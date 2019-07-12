# Journal 5
## Array Methods

    var myPets = ['Tangerine', 'Malaki', 'Cookie'];

    myPets.push('bob);
    console.log(MyPets);
    >[ 'Tangerine', 'Malaki', 'Cookie', 'bob' ]

   _____________________________________________

    //PUSH: puts an item at the end of an array

    var userNames = []

    userNames.push('Zerek');
    console.log(userNames);
___
    //POP: Takes off of the end and returns it

    var myPets = ['Tangerine', 'Malaki', 'Cookie'];

    myPets.pop();
    console.log(myPets);
___
    //UNSHIFT: add to the beginning

    var mypets = ['Tangerine', 'Malaki', 'Cookie'];

    mypets.unshift('Bob');
    console.log(mypets);
___
    //SHIFT: takes one away from the beginning
    mypets.shift();
    console.log(mypets)
___
    indexOf: returns the index of the item in the array
    mypets.indexOf('Malaki);
    console.log(mypets);
    >1
___
    //splice
    splice:(index to begin the splice, number of items to remove, elements to add- returns the elements that were removed)
    //splice adds or removes items, or both
### Example 1
    mypets.splice(1, 0, 'Bob);
    //(begins at 1 in this case , removing 0 in this case , 'Bob' is being added behind [1] because that was our starting point)

    console.log mypets.splice(1, 0, 'Bob');
    >['Tangerine', 'Bob', 'Malaki', 'Cookie']
### Example 2
    mypets.splice(1, 0, 'bob', 'sue')
    console.log(mypets.splice(1, 0, 'bob', 'sue'))
    >['Tangerine', 'Bob', 'sue', 'Malaki', 'Cookie']

# Assignment:
### 1 Make an Array with at least 5 items
### 2 Add three items to the end
### 3 Remove one item from the end
### 4 add one item to the beginning
### 5 Remove two items from the beginning
### 6 Put something in the middle of the array
### 7 Remove two items from the middle of the array

### _* Splice is a powerful command that can do all of this._

## Consider the example, when using functions and arrays for interchangeable information:
    function sayHi(firstName, lastName){
        var userName = firstName + ' ' + lastName;
        var greeting = 'Hello ' + userName;
        console.log(userName, greeting);
        return [userName, greeting];
    }

    // var greet = sayHi('James', 'Dansie');
    // console.log(greet[1]);
    sayHi('Julie', 'Erlemeir')[0];
    
    'return'>Julie Erlemeir Hello Juli Erlemeir
    console>'Julie Elemeir'
## Practice
### - Write a function that takes in three numbers added together, along with a string that says _'the sum of the three numbers is'_ and then the sum. Return both in an array.

    function addNumbers(num1, num2, num3){
    var mathequal = num1 + num2 + num3;
    var returnstatement = 'the sum of the three numbers is ' + mathequal;
    return [mathequal, returnstatement];
    }

    addNumbers(5, 10, 1);
    return>[ 16, 'the sum of the three numbers is 16']
    
___
___
___
# Git Branch
### 1. Make a new branch:
    git checkout -b branchname
### 2. A-C-P Git Push Origin branchname
### 3. Get changes _from master _in_ master => checkout master
    git pull origin master
