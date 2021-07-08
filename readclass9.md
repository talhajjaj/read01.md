**Functional Programming Concepts**
- What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .

- What is a pure function and how do we know if something is a pure function?
It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects, and it's It returns the same result if given the same arguments

- What are the benefits of a pure function?
The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:
Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D

- What is immutability?
 immutability is important to make our functions more consistent and predictable. The idea is to build a new collection with all absolute values.
- What is Referential transparency?

 if a function consistently yields the same result for the same input, it is referentially transparent.
pure functions + immutable data = referential transparency
With this concept, a cool thing we can do is to memoize the function.


**Node JS Tutorial for Beginners #6 - Modules and require()**

What is a module?
What does the word ‘require’ do?
How do we bring another module into the file the we are working in?
What do we have to do to make a module available?