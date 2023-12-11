# Clean code

1-Give to variables, methods, or other attributes in the code good meaningful names. The name must demonstrate what an item represents cohesively, this is essential for a good understanding of the code.

2- Create small methods. With smaller methods, implementing fewer functionalities, we increase the possibility of reusing this method in other changes and make it more cohesive. Also, methods should not receive a lot of parameters, trying not to use more than three.

3- Avoid repetitive code, with a lot of conditional structures or nested loops. It generates a code that is unnecessarily complex and confusing.

4- Code comments must be used only when necessary, the code must be clean enough to be read and understood without comments. Programmers can also forget to change comments when the code is updated, and the comments can reflect something that the code is not doing anymore.

5- Use the boy scouts rule that says “Always leave the campground cleaner than you found it”. The same should be done when coding, every time you change an implementation it’s important to make the code cleaner than it was before.

6- Besides using these statements in the code that implements the business rules, it’s also important to implement clean tests. Tests must be clear, consistent, testing small pieces of functionalities — testing in parts also helps us to locate pieces of code that could fail and cause problems.
