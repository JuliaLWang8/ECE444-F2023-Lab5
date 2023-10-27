# ECE444-F2023-Lab5
 
This lab is an example of utilizing test-driven development (TDD) for a simple blogging application using Flask, JavaScript, BootStrap, and SQLAlchemy. 

### What are the pros and cons of TDD?
Pros: 
* Faster debugging: TDD allows for early bug detection and since we are creating tests as development is being done. This makes it easier to locate and fix the problem before it becomes deeply embedded.
* Documentation and readability: others can refer to the tests to understand the functionality and how the code is supposed to work. This will help other developers collaborate when working on the same codebase. 
* Refactoring: TDD allows for developers to refactor the code knowing that any incorrect additions would be fail the tests. This makes it easier to implement changes that do not break anything.
*  Use cases: since TDD encourages developing each feature at a time, this allows for developers to reflect on use cases of each feature rather than the whole code, thus considering user needs at each step.

Cons:
* Time to write tests: writing tests for each feature may be time consuming for developers, especially for an application with many features. This may not be the best utilization of the developers time.
* Updating tests: when requirements change, all tests poentially need to be updated, which can lead to extra work. 
* Not compatible with projects: some projects which are more experiment focussed may not be compatible with TDD since the tests would constantly need to be updated.
* Edge cases not guaranteed: TDD is subject to human error where the developer doesn't consider all possible test cases. This may lead to missing edge cases and issues. 