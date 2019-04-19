DONE!

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. Describe the biggest difference between `.forEach` & `.map`.

            The .forEach method doesn't create a new array when it executes a function but .map does.

2. What is the difference between a function and a method?

            A method is like a function but it is a property of an object where a function is not.

3. What is closure?

            A closure is a part of code that combines functions and lexical environment. Anything that is declared within that lexical environment can be called within that environment scope and not outside of it.

4. Describe the four rules of the 'this' keyword.

    Principle 1: Window/Global Object Binding
            The value of the .this keyword will be in the window/console object when it's in the global scope
    
    Principle 2: Implicit Binding
            A function is bound by the object that preceeds the dot
    
    Principle 3: New Binding
            The new binding creates new objects from an already existing constructor function
    
    Principle 4: Explicit Binding
            "this" is explicitly defined when JS call or apply method is used

5. Why do we need super() in an extended class?
            To access and call functions on an object's Parent.
