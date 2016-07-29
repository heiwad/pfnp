# Programming for Non Programmers

# JavaScript Workout

In the following set of activities, you are going to start to get familiar with JavaScript.
Some of it might feel a bit like magic. That's ok.

## Part 1: Hello Javascript ##

[Hello World](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) is a programmer's rite of passage so it's as good a place to start as any.

We'll start working in the JavaScript Console.

To get started, open the Chrome JavaScript Console.
View -> Developer -> JavaScript Console

1. Paste the following in to the console.

        console.log("Hello World!");

2. Text can be glued together in JavaScript.

        console.log("Hello" + " " + "World" + "!");

3. It can also be saved in a variable

        var myText = "Hello World!";  
        console.log(myText);  

4. If you wanted to really shout your message out to the world you could also try the following:

        alert(myText);
        

5. We can also get text from the user and save it too!

        var inputText = prompt("What's your name?");
        console.log(inputText);


### Code Challenge:  
> Ask the user for their favorite color and say something about it back to them!  
> For example if I told you my favorite color is yellow,  
> You would print "No way, yellow is my favorite color too!"
        

## Part 2: A bit more JavaScript

Types of things
* Numbers
* Boolean
* null
* undefined
* Text
* Lists
* Objects (dictionaries)

### Math !

We can do math in the console.
```
>>> 2 + 2
4
>>> 2 * 3.5
7.0
>>>
```

### Practice question - try these out in the console:
```
1. 2 * 7 * 3.5
2. 3 + 5 - (2 * 6)
3. (3 + 5 - 2) * 6
4. 4 == 5
5. 5 == 5
6. 4 < 5
7. 5 >= 4
8. 9 != 9
9. 8 != 9
```

### Assignment vs Equality Check

```
>>> x = 2
>>> x == 5
>>> x = 5
```

# Practice problems
```
- Set a variable called `name` equal to your full name.
- Set a variable called `first_name` equal to your first name.
- Set a variable called `last_name` equal to your last name.
- Then combine `first_name` and `last_name` so that it equals your full name, and save this in a variable called `full_name`.
- Prove using the == operator that they are equal.
```

Todo:
Lists - add to list. get items back from the list
Objects or Dictionaries - add names, phone numbers, get them back

Create Your OwnFunction
Functions (built in text functions)

Custom Multiplier

    function myMultiplier (number1, number2) {
            return number1 * number2;
    }

What if we want to use info from prompt to do math?  
We may have to tell JavaScript that it's a number using parseInt(myText)
Let's try it and see what happens

    var input = prompt("How old are you?");
    age = parseInt(input);
    console.log("Next year you'll be: " + (input+1) );
    console.log("Next year you'll be: " + (age+1));


### What was the result?        
    
 
## Control Flow

### Loops


Here's how you can loop over all positions in a list

    var myList = ['bob','billy','bo'];
    for (position in myList) {
        console.log(myList[position])
    }

You can also do something similar with dictionaries but you'll get back a 'key' instead of a position

    var sounds = {"cat":"meow","dog":"woof","owl":"hoot"};
    for(animal in sounds){
        var sound = sounds[animal];
        console.log("The " + key + " says " + sound + "!");
    }
    
Looping with a counter

    for (var i = 0; i < 9; i++) {
        console.log(i);
    }
    
You can also loop with counters over the lists
    
    var myList = ['jane','jill','jackie'];
    for (var i = 0; i < foo.length; i++) {
        console.log(myList[i]);
    }

### Conditionals

Our programs always do the same thing. What if we wanted it to be able to do something different depending on what the user did? We can use IF statements.



Callbacks
Scope of Variables

For more JavaScript Exercises Try [IntroComputing.org](http://introcomputing.org/)

More JavaScript Types: Null, Undefined, Symbol [MDN JavaScript Data Structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)


Getting Data from the Internet [via StackOverflow](http://stackoverflow.com/questions/247483/http-get-request-in-javascript)
Getting Data From [Giphy API](https://github.com/Giphy/GiphyAPI#random-endpoint) 
