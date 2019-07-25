# *Week 2*
## _Javascript_
## - Key Value Pairs
_[will insert text from repl here]_
<br>
___ 
___
## _DOM_
### _[Document Object Model]_
<br>
Using JS to insert images to html, without touching html 
<br>

    'use strict';

    var cookie = {
        name: 'Cookie',
        type: 'dog',
        breed: 'brown',
        age: 8,
        isLoud: false,
        sheds: true,
    }

    var tangerine = {
        name: 'Tangerine',
        type: 'cat',
        breed: 'orange',
        age: 4,
        isLoud: true,
        sheds: true,
    }

### Render Function
Three things:
1. Create an element - li
Helps to narrow down with class or id<br>
   > _var liEl = document.createElement('li');_
2. give it content - name
    > _liEl.textContent = this.name;_
3. append it to the DOM



Store the DOM node in a variable
    var ulEl = document.getElementById('pet-list'); 
    <!-- //there is only one id, per definition of id -->
