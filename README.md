[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Documentation Treasure Hunt

<!-- MATERIALS METADATA -->
<!--
  title: MDN Documentation Treasure Hunt
  format: exercise
  duration: 45 min
  original author: Matt Brendzel
  tags: core, javascript, documentation
-->

Today's we're going to be hunting for information in the Mozilla Developer
Network's [JavaScript documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
For this exercise, we'd like you to _only_ use the MDN -- that way, you get
very comfortable looking things up there.

Each clue below has a certain number of points associated with finding the
correct answer. If you're not sure, take a guess, since you won't lose points
if you're wrong.

Ready.... Set..... Go!!!

## 1 Point Each

-   What method would turn "a few words" into `["a", "few", "words"]`?

    > [The String method `.split`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split)

-   What property of an array tells you how many elements are inside it?

    > [The `.length` property](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/length)

-   What method could you call to get the current time?

    > [`Date.now()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date/now)
    > You can also get the current time by creating a new Date
    > object (`new Date()`) with no arguments, since this will default to the
    > current time, and then accessing the properties (hours, minutes, etc)
    > on that object.

-   Which type of statement evaluates an expression, matches the expression's
    value to a particular case, and executes code associated with that case?

    > [A `switch` statement](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch)

-   What new JavaScript feature allows you to set read-only constants in
    your code?

    > [The `const` declaration](https://developer.mozilla.org/en-US/search?q=const)

-   What method can you call to get a list of all of the properties on an
    object?

    > [`Object.keys(someObj)`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/keys)
    > will give you all enumerable (i.e. listable) keys on that object.

## 2 Points Each

-   What Array method plugs every element in the array into a function, one at
    a time, and returns a new array containing the results?

    > [The `.map` method](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

-   What method could we call to generate a random number between 0
    (inclusive) and 9 (exclusive)?

    > Call [Math.random()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
    > and multiply the result by 9.

-   What method can you call to fill all of the elements of an array with the
    same constant value?

    > [`.fill`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/fill)

## 3 Points or More

-   (Up to 3 pts) What method(s) would allow you to extract the string 'rag'
    from the string 'enrage'? 1 pt for each method.

    > [`.slice`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/slice),
    > [`.substring`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substring),
    > and [`.substr`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/substr)

-   (3 pts) What type of Object represents a pattern of text that you can
    search for inside a String?

    > A [`RegExp`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp),
    > a type of object which represents a [Regular Expression](https://en.wikipedia.org/wiki/Regular_expression).

-   (4 pts) Suppose that we wanted to run some code that we thought might hit an
    error -- for instance, trying to contact a server, and getting no response.
    What group of statements would allow us to try out some code, and if it
    errors out, recover by running some other code?

    > [`try`/`catch` statements](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch)

-   (5 pts) What method iterates through an array one element at a time and
    calls a function, passing in as arguments
    (a) the current element, and
    (b) the function's previous result
    ?

    > [`.reduce`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/Reduce)

-   (5 pts) What type of Object is used to represent (and stand in for) the
    output of an operation that hasn't finished running?

    > A [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
