# General Advice For Writing Clean Code

Keep these main principles in mind when writing code for producing more understandable programs. There are hundreds of specific pieces of advice and rules for achieving these goals, but it's important to keep the goals in mind so that you know why you're following those rules and how/when to break them appropriately.

## 1. Write For People, Not the Computer

Make it the primary concern to produce code read by a human. Unless you violate a syntax rule, the computer will be able to execute the code no matter how it is formatted. Humans (including your future self), on the other hand, need more help.

Make the computer your secondary concern, and prioritize yourself and the other programmers working in your codebase.

## 2. Be A Textbook Writer, Not a Poet

There is a place for creativity, lightheartedness, and fun in the world of computer programming. But, in a shared codebase that grows and changes over time — especially one that represents an important product like academic research or a widely used service — it's more important to be clear and concise than fun. 

You probably wouldn't try to write a calculus textbook in iambic pentameter. Similarly, it's better to approach your code with a serious intent and a consistent style. 

## 4. Use Comments For "Why" Rather Than "What"

To the extent it is possible your code should be self descriptive. The code should tell a reader what the code does. If the code is confusing or unclear, try to rewrite the code in a manner that is clear instead of adding a comment to explain the confusing code.

Use comments to explain your intent rather than to describe the code. An example of a helpful comment is: "We are sorting this array because it makes the following logic much simpler." This tells future programmers something that the code itself cannot say, and helps future readers understand why you made certain choices.

## 5. Use Functions For Grouping and to Avoid Repetition

Functions are great for breaking up long blocks of code into smaller, logical blocks. Programmers can use functions the same way writers use paragraphs, sub-headings, and chapters. By breaking logic into smaller blocks the code becomes easier to test, (usually) easier to read, and easier to refactor. 

Functions are also great for reusing logic that appears in more than one place. If you find yourself using a mathematical formula, boolean equation, or series of data pre-processing steps repeatedly then you should probably pull that code into a function and use it instead of duplicating the logic. This makes the code easier to test. If you find a bug in the logic, you'll only have to fix it in one place. And, you'll save time copy/pasting the logic for that function.

Whenever possible, keep functions short. Use fewer parameters whenever possible. Long function declarations are confusing, just like long function bodies are confusing.

## 6. Use a Style Guide

Similar to magazines and journals maintaining a style guide for writing prose, most software companies maintain a style guide for the programming languages they use. Analogous to how there are disagreements in the English world about using the Oxford Comma, there are stylistic disagreements in the programming community about topics such as tabs vs spaces, how many blank lines to put between function definitions, and where to put curly braces.

Agreeing on a style guide can help programmers avoid endlessly arguing about contentious stylistic issues. Have the argument once as a team, agree on a style guide, then follow it. Most IDEs (Integrated Development Environments) and text editors support "[linters](https://en.wikipedia.org/wiki/Lint_(software))" that can identify many style guide violations with red underlining, which can also be visually helpful.

## 7. Don't Be Dogmatic

Every rule has exceptions. Keep an open mind when writing and reviewing code. If following a particular rule in the style guide (or some other rule of thumb) makes the code harder to understand, consider making an exception to the rule. 

# Python vs R 

