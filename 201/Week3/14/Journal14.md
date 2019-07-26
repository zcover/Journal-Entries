# Class 14
## Project Week: What it looks 
Step One:
>Minimum Viable Product (MVP)
<br>
Expectation is to meet MVP by wednesday.<br>

Presenting at 1pm Friday.
## Homework during Project week
Project Week Reports:
>Individual report which says how things are going, how we are contributing to the report, and what our group is doing.<br>
How is the group working together?<br>
<br>
Is your team working _well_ together? (In a high stress environment)

 *Acknowledge eachother's wins
___
# Modularizing CSS
(Modularizing ia allowing code to work together, an example is how we make functions do one thing and one thing only, so it can work with any code system to do the same thing, making it _modular_)

## Transform tag
    element {
        transform [type]
    }

    >will add animation to a specific element of the page, where assigned.
<br>

## Hover
    element-id:hover{
        css_styling_choice
    }
    >places effect on hover-over

<br>

## Transition
    element {
        transition:2s;
    }
    >Delays animation, or whatever, for 2 seconds (can change time)

## Keyframes
Key frames are the _functions_ of CSS

    #box1 {
        animation: fadeIn 5s infinite
    }
    
    
    @keyframes fadeIn{ //this is a made up term
        0% {
            opacity: 0;
        }
        50% //time {
            opacity: 1;
        }
        75% {
            opacity: 1.5;
        }
        100% {
            opacity: ;
        }
    }
<br>

## Infinite
Note that the time (in seconds) listed for animations is actually the length of the animation. <br>

Using _"Infinite"_ has the animation loop infinitely


