# pfnp

# Intro To Javascript #

In the following set of activities, you are going to start to get familiar with JavaScript.
Some of it might feel a bit like magic. That's ok.

## Part 1: Hello Javascript ##

[Hello World](https://en.wikipedia.org/wiki/%22Hello,_World!%22_program) is a programmer's rite of passage so it's as good a place to start as any.

We'll start working in the JavaScript Console.

To get started, open the Chrome JavaScript Console.
View -> Developer -> JavaScript Console

1. Paste the following in to the console.

    console.log("Hello World");

2. Text can be glued together in JavaScript.

    console.log("Hello" + " " + "World" + "!");

3. It can also be saved in a variable

        var myText = "Hello World!";  
        console.log(myText);  

4. If you wanted to really shout your message out to the world you could also try the following:

`alert(myText);`

(Please never do that)

5. We can also get text from the user and save it.

`var inputText = prompt("What's your name?");`

6. You can print that message back to the console!

`console.log(inputText)`

## Ok text is ok. But what else can I do?

Math - Numbers in javascript are a little strange. That's ok
Lists
Objects or Dictionaries

Functions (built in text functions)
Control Structures(Skip)
Callbacks (Skip)


Do some match function



### Paste the Following JavaScript code into the Console
Note: Ignore the warning about the method being deprecated. It means that you shouldn't use this technique on a real website because a) it's poor form for users and b) in the future, they might stop supporting it so your site may stop working.

    function httpGet(theUrl)  
    {  
        var xmlHttp = new XMLHttpRequest();  
        xmlHttp.open( "GET", theUrl, false ); // false for synchronous request  
        xmlHttp.send( null );  
        return JSON.parse(xmlHttp.responseText);  
    }  

Note [via StackOverflow](http://stackoverflow.com/questions/247483/http-get-request-in-javascript)
