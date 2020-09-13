# spaghetti-and-quines
## Inspiration

I haven't listened to rap in a while (I almost never do), so I decided to revisit one of my favorites this week: Eminem's "Lose yourself" song. I don't think I have to say that it was awesome, but it was! Just a few days ago I learned about a concept in programming called *quines*, and what they are, how they function, and it's beautiful intricacies. They say quines are the pinnacle art form in programming because of what people can come up with it. Anyways, I thought about Eminem's parody song "Mom's Spaghetti" and quines and I thought... "Wouldn't be awesome if there was a quine of spaghetti code that prints an ascii image of spaghetti?" And so, everything just fell into place.

## What it does

Basically, a quine is a "*self replicating*" program that takes in no input, and outputs itself. Here, I've gathered the worst practices in the history of python programming which include mixed cases, camel case, snake case, minified variable names, too many comments in one function but none in another, functions that don't do anything and aren't called, etc. This, in essence is spaghetti code, code that is pretty much like copied straight from stackoverflow.

## How I built it

A quine is classified as a program that takes no input and a quine. However, a quine should not use any 'open()' function to print out its source code, rather it must print out its own code via print statements or otherwise. For the spaghetti-ness part, I looked back into my early programming days and straight copy and pasted my code into this quine. Then, I tried to work out the character escapes and notation inside the string to be printed, so that it can print itself. This is perhaps one of the easiest ways to create a quine: to define a string, then put the string inside itself with string formatting. Unobfuscated, you can clearly see that this code may just be the *worst, most disgusting, unpythonic piece of code you've ever seen in your entire life*, but it works.... and that's all that matters.
