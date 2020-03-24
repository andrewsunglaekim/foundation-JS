# FoundationsJS

This isn't software, this is a readme repo.

I couldn't figure out a great title for this group of courses. I kind of just wanted to take a jab at software named with JS after it.
That said, I didn't think labeling something like "intermediate js" or "advanced js" was appropriate for a series like this.

It runs an array of learning objectives that are both "beginner" and "advanced" with nuances in between.

The objective behind this group of lessons is to enhance our understanding of important principles of software as it pertains to javascript.
Less about specific syntax and more about identifying patterns and principles... by looking at specific syntax. We'll dive into code and discuss
it top to bottom.

Though the individual lessons run independent of each other, there is a bit of context in all the lessons that helps with the next lessons.
The context isn't strictly necessary to understand the class, but hopefully you want the whole package deal!

Here are each of the lesson titles and their corresponding learning objectives.

> Most of the things in the lesson plans that will be taught will be factual, there are other things
that are just my opinion on things. Each lesson is about 75 mintues give or take. I'll try my best to give you some time back.

## Lesson 1: Functions, SemanticJS, Abstractions, and maybe not so great Abstractions
- Define Abstraction
- Identify the inputs of a function
- Identify the outputs of a function
- Identify the side effects of a function
- Define Functional Programming
- Identify potential anti patterns in code structure
- SemanticJS
- Acknowledge the subjectivity of engineering

## Lesson 2: JS Scope and context
- Describe scope and how it governs how data is able to be accessed in code
- Differentiate between var, let, and const keywords in variable assignment
- Differentiate between global, local, and block scope
- Explain Javascript context and how the value of the 'this' is derived
- Explain the default context of Javascript executing in the browser
- Use `.call`, `.apply`, `.bind` to explicitly set context
- Explain how "lexical binding" works with arrow functions
- Use console.log(this)

## Lesson 3: Asynchronous JS and the message queue
- Define Javascript as a single threaded language within the browser
- Explain how javascript functions "run to completion"
- Define "execution context"
- Determine the composition and execution order of the javascript call stack
- Identify the problem that asynchronous program execution solves
- Describe the concurrency model of JS based on the "event loop"
- Give an example of how the message queue is leveraged in javascript.
- Leverage promises to handle asynchronous behavior
- Identify a distinction between tasks and micro tasks.

## Lesson 4: Promise returns and Async/await
- Define a promise
- Leverage `.then` to handle successful async functionality
- Leverage `.catch` to handle unsuccessful async functionality
- Leverage `.finally` to handle any async functionality
- Pass returned values to chained promises
- Use Promise.all to handle multiple async functionalities
- Use promise chaining to nest async functionality
- Identify when you would choose Promise.all or promise chaining
- Leverage async/await as syntactic sugar for promises to clean up promise chains
