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
Six data types that are primitives:
Boolean
Number
String (Text)
Object

Numbers
Text
Lists
Objects (dictionaries)

Math - Numbers in javascript are a little strange. That's ok
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

### For Loops

A basic 'for' loop 

    for (var i = 0; i < 9; i++) {
        console.log(i);
    }

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
    
If you want more control over which positions get printed you can also create a variable
    
    var myList = ['jane','jill','jackie'];
    for (var i = 0; i < foo.length; i++) {
        console.log(myList[i]);
    }

Control Structures(Skip)
Callbacks (Skip)
Scope of Variables

For more JavaScript Exercises Try [IntroComputing.org](http://introcomputing.org/)

More JavaScript Types: Null, Undefined, Symbol [MDN JavaScript Data Structures](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures)


Getting Data from the Internet [via StackOverflow](http://stackoverflow.com/questions/247483/http-get-request-in-javascript)
Getting Data From [Giphy API](https://github.com/Giphy/GiphyAPI#random-endpoint) 
