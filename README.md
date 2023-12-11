# Clean code

1-Give to variables, methods, or other attributes in the code good meaningful names. The name must demonstrate what an item represents cohesively, this is essential for a good understanding of the code.

2- Create small methods. With smaller methods, implementing fewer functionalities, we increase the possibility of reusing this method in other changes and make it more cohesive. Also, methods should not receive a lot of parameters, trying not to use more than three.

3- Avoid repetitive code, with a lot of conditional structures or nested loops. It generates a code that is unnecessarily complex and confusing.

4- Code comments must be used only when necessary, the code must be clean enough to be read and understood without comments. Programmers can also forget to change comments when the code is updated, and the comments can reflect something that the code is not doing anymore.

5- Use the boy scouts rule that says “Always leave the campground cleaner than you found it”. The same should be done when coding, every time you change an implementation it’s important to make the code cleaner than it was before.

6- Besides using these statements in the code that implements the business rules, it’s also important to implement clean tests. Tests must be clear, consistent, testing small pieces of functionalities — testing in parts also helps us to locate pieces of code that could fail and cause problems.

# Refactoring

## 1. What is Refactoring?
- Refactoring is the process of making small, incremental improvements to code without changing its external behavior.
- It is done to enhance code readability, maintainability, and design.

##2. Why Refactor?
- Improve code readability: Make the code easier to understand for yourself and others.
- Simplify complex logic: Break down complex functions or methods into smaller, more manageable pieces.
- Enhance maintainability: Make it easier to maintain and extend code over time.
- Reduce redundancy: Eliminate duplicate code to make the codebase more DRY (Don't Repeat Yourself).

## 3. Common Refactoring Techniques:
- Extract Method: Turn a portion of code into a separate function or method to improve clarity.
- Rename Variable/Method: Use descriptive names for variables and methods to enhance understanding.
- Extract Class: Group related methods and data fields into a new class for better organization.
- Move Method/Field: Transfer a method or field to a more appropriate class.
- Replace Conditional with Polymorphism: Use polymorphism to replace complex conditional statements.

## 4. Code Smells:
- Code smells are signs that your code may benefit from refactoring.
- Examples include long methods, large classes, and repeated code.

## 5. Refactoring Tools:
-Use automated refactoring tools to assist in making changes safely.

## 6. Working with Legacy Code:
- Legacy code can be improved gradually through refactoring.
- Write tests to ensure that existing functionality is preserved during refactoring.

## 7. The Refactoring Process:
- Start with a set of tests to ensure existing functionality.
- Make small, incremental changes, testing at each step.
- Ensure that the code remains functional after each refactoring step.

## 8. Communication and Collaboration:
- Refactoring is a collaborative process; communicate changes with your team.
- Use version control systems to track and manage changes.

## Best Practices of Code Refactoring
- Refactor codes regularly to maintain code quality and also reduce technical debt.
- Minimize the risk of adding unnecessary bugs by refactoring the codebase in small chunks.
- Do not forget to validate the functionality of the codes against the required external behavior after refactoring codes.
- Follow the eat the frog approach in a refactoring project. It means prioritizing areas that affect multiple parts of the codebase or are difficult to understand.
- Use a version control software or web app to maintain different versions of the refactored code and go back to the best-known version when needed. 
- The code refactoring project must involve everyone from the DevOps team.
- Create a code refactoring document or logbook and record the reasons and approach behind each refactoring session for future reference. 
- It is recommended to refactor code when reviewing the software, mobile app, or web app for audit purposes. 
