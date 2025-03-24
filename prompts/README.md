# Example prompts

## Course 1: Intro to GenAI and Software Dev

### Write a program to add 2 numbers:

```
Can you write a python function to add two numbers named a and b and return the result?
```

```
Create a javascript function that adds 2 numbers
```

```
Create a C# method that adds 2 numbers
```

<b>Note</b>: Specificity and Domain knowledge are important


### Iterative prompting

Initial prompt

```
Write a Javascript function to check if a number is a prime
```

Add error handling
```
update the function to include error-handling for non-integer and non-positive output
```

Add documentation

```
add detailed comments that explain this code. Highlight any complex parts that might require deeper explanation
```

### Debug with LLM

```
help me find an error in this code

INSERT CODE SNIPPET
```

### Give LLM feedback

Initial prompt

```
Write a python function to calculate the factorial of a number
```

Feedback: error handling

```
Please modify the function to include a check that ensures the input is a non-negative number
```

### Assign role to LLM

Prompt 1:

```
Write a python function to calculate the factorial
```

Prompt 2: (role assigned)

```
As my Python mentor, please write a python function to calculate the factorial and explain how it works
```

### Multiple roles

```
As a software architect and a security expert, please evaluate this Python script for a web application and suggest architectural improvements and security enhancements

[INSERT CODE SNIPPET]
```

### Expert Level roles

Code critique: `As a open source contributor, ...`

Enhance feature: `As a [Domain] expert, ...`

Finding edge cases: `As a software tester, ...`


