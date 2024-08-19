# Assignments

## Simple tasks

1. Print "Hello world!" to the console.

   - Write a function that prints "Hello world!" to the console.
   - Example usage:
     ```python
     hello_world()
     ```
     Example output:
     ```
     Hello world!
     ```
   - Hint: no hint is needed for this

2. Sum of two numbers.

  - Write a function that prints that takes two numbers as input and prints their sum to the console.
  - You should validate the arguments and raise an error if they are not numbers.

   - Example usage:
     ```python
     print(sum(10, 20))
     print(sum("Hello", 20))
     print(sum(10))

     ```
     Example output:
     ```
     30
     Must be numbers
     Must be numbers 
     ```
  - You can use the `isinstance` function to check the type of a variable.
  - You can use control flow to check if the number of arguments is correct.

3. Check if a number is even or odd.

   - Write a function that checks if a number is even or odd.
   - The function should return "Even" if the number is even and "Odd" if the number is odd.
  - You should validate the arguments and raise an error if they are not numbers.
   - Example usage:
     ```python
     print(even_or_odd(10))
     print(even_or_odd(23))
     print(even_or_odd("Hello"))
     ```
     Example output:
     ```
     Even
     Odd
     Must be numbers
     ```
  - Hint: you can use the modulo operator `%` to determine if the number is divisible by 2.

4. Maximum of three numbers.

  - Write a function that takes three numbers as input and returns the maximum of the three numbers.
  - The function should return the maximum of the three numbers.
  - You should validate the arguments and raise an error if they are not numbers.
   - Example usage:
     ```python
     print(max_value(10, 20, 30))
     print(max_value(23, 10, 5))
     print(even_or_odd("Hello"))
     ```
     Example output:
     ```
     30
     23
     Must be numbers
     ```
  - Hint: use the `max()` function to get the maximum of the three numbers.

5. Factorial of a number.

  - Write a function that calculates the factorial of a number.
  - The function should return the factorial of the number.
  - You should validate the argument and show an error if it is not a number.
   - Example usage:
     ```python
     print(factorial(5))
     print(factorial("Hello"))
     ```
     Example output:
     ```
      120
      Must be a number
     ```
  - Hint: use loop to calculate the factorial
  - Hint: you can also use recursion to calculate the factorial. (recommended)
  - Hint: read about recursion here: [Recursion](https://realpython.com/python-recursion/)
  - Hint: read about factorial here: [Factorial](https://en.wikipedia.org/wiki/Factorial)

6. String reversal.

  - Write a function that takes a string a reverses it.
  - The function must take a string and return the reversed string.
  - You should validate the argument and show an error if it is not a string.
   - Example usage:
     ```python
     print(reverse_string(5))
     print(reverse_string("Python"))
     ```
     Example output:
     ```
      Must be a stirng
      nohtyP
     ```
  - Hint: use slicing (`[::-1]`) or a loop to reverse the string.

7. List length

  - Write a function that takes a string or list and reverses it.
  - You should validate the argument and show error if it is not a string.
   - Example usage:
     ```python
     print(list_len([1, 2, 3, 4, 5, 6, 7]))
     print(reverse_string("Python"))
     ```
     Example output:
     ```
      7
      6
     ```
  - Hint: use the `len()` function.

7. Fibonacci series

  - Write a function that generates the first `n` numbers in the Fibonacci series.
  - You should validate the argument and show an error if `n` is not a number.
   - Example usage:
     ```python
     print(fibonacci(5))
     print(fibonacci("Python"))
     ```
     Example output:
     ```
      [0, 1, 1, 2, 3]
      Must be a number
     ```
  - Hint: use the `len()` function.

7. Count vowels in a string.

  - Write a function that counts the number of vowels in a string.
   - Example usage:
     ```python
     print(count_vowels("Hello world"))
     print(fibonacci("Python"))
     ```
     Example output:
     ```
      3
      1
     ```
  - Hint: use a loop to iterate over the string and count the vowels.
  - Hint: you can use the `in` operator to check if a character is a vowel, read about it here: [in operator](https://www.w3schools.com/python/ref_keyword_in.asp)

8. Palindrome check

  - Write a function that checks if a string is a palindrome.
  - Returns true if is a palindrome and false if it is not.
  - Example usage:
     ```python
     print(is_palindrome("madam"))
     print(is_palindrome("Python"))
     ```
     Example output:
     ```
      True
      False
     ```
  - Hint: compare the string with its reverse to check if it is a palindrome.
  - Hint: read about palindromes here: [Palindrome](https://en.wikipedia.org/wiki/Palindrome)

8. Sum of a list

  - Write a function that calculates the sum of a list of numbers.
  - Example usage:
     ```python
     print(sum_list([10, 20, 30, 40]))
     ```
     Example output:
     ```
      100
     ```
  - Hint: use a loop to iterate over the list and calculate the sum.
  - Hint: you can also use the built-in `sum()` function to calculate the sum of a list. Read more about it here: [sum()](https://www.w3schools.com/python/ref_func_sum.asp)

9. Dictionary search

  - Write a function that takes a dictionary and a key as input and returns the value of the key.
  - Example usage:
     ```python
     person = {"name": "John", "age": 30}
     result = find_in_dict(person, "name")
     print(result)
     result2 = find_in_dict(person, "gpa")
     print(result2)
     ```
     Example output:
     ```
     John
     Key not found
    ```
  - Hint: use the `get()` function to get the value of the key.
  - Hint: read about dictionaries here: [Dictionaries](https://www.w3schools.com/python/python_dictionaries.asp)
  - Hint: read about the `get()` function here: [get()](https://www.w3schools.com/python/ref_dictionary_get.asp)

9. Dictionary search

  - Write a function that takes a dictionary and a key as input and returns the value of the key.
  - Example usage:
     ```python
     person = {"name": "John", "age": 30}
     result = find_in_dict(person, "name")
     print(result)
     result2 = find_in_dict(person, "gpa")
     print(result2)
     ```
     Example output:
     ```
     John
     Key not found
    ```
  - Hint: use the `get()` function to get the value of the key.
  - Hint: read about dictionaries here: [Dictionaries](https://www.w3schools.com/python/python_dictionaries.asp)
  - Hint: read about the `get()` function here: [get()](https://www.w3schools.com/python/ref_dictionary_get.asp)

10. Prime number check
  - Write a function that checks if a number is a prime number.
  - Returns true if the number is prime and false if it is not.
  - Example usage:
     ```python
     print(is_prime(7))
     print(is_prime(10))
     ```
     Example output:
     ```
     True
     False
    ```
  - Hint: use a loop to check if the number is divisible by any number other than 1 and itself.
  - Hint: read about prime numbers here: [Prime numbers](https://en.wikipedia.org/wiki/Prime_number)

11. Number of words in a string
  - Write a function that counts the number of words in a string.
  - Example usage:
     ```python
    print(count_words("Hello world"))
    print(count_words("This is a test sentence."))
     ```
     Example output:
     ```
     2
     5
    ```
  - Hint: use `split()` function to split the string into words.
  - Hint: read about the `split()` function here: [split()](https://www.w3schools.com/python/ref_string_split.asp)

12. Simple calculator.
  - Write a function that acts as a simple calculator, it takes two numbers and an operator (as a string) and return the result
  - Example usage:
     ```python
    print(calculator(10, 5, "*"))
     ```
     Example output:
     ```
     50
     ```
  - Hint: use conditionals to check the operator and perform the operation.


Make sure to document your code and make sure they work as expected.
DO not hesistant to ask for help if you are stuck.
