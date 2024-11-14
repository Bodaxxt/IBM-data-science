# IBM-data-science
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "#1. Write a Python program to print the following message on the screen:\n",
    "#\"Hello, Python learners! Today we start our coding journey.\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 35,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Hello, Python learners! Today we start our coding journey.\n"
     ]
    }
   ],
   "source": [
    "print(\"Hello, Python learners! Today we start our coding journey.\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Challenge: Print a multi-line message using triple quotes that includes your name and \n",
    "favorite programming language."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 36,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "\n",
      "abdallah ayman\n",
      "19 \n",
      "data science\n",
      "\n"
     ]
    }
   ],
   "source": [
    "print(\"\"\"\n",
    "abdallah ayman\n",
    "19 \n",
    "data science\n",
    "\"\"\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Create a variable called age and assign it your age. Print a message that says, \"I am \n",
    "[age] years old."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 38,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "I am 19 years old. \n"
     ]
    }
   ],
   "source": [
    "age = 19\n",
    "print(f\"I am {age} years old. \")\n",
    "\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Challenge: Create three variables of different data types (integer, float, and string). Print \n",
    "each variable with a description of its data type."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 39,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "\n",
      "int = 10\n",
      "flout = 3.3\n",
      "string = abdallah\n",
      "\n"
     ]
    }
   ],
   "source": [
    "int =10\n",
    "f = 3.3\n",
    "s =\"abdallah\"\n",
    "print(f\"\"\"\n",
    "int = {int}\n",
    "flout = {f}\n",
    "string = { s}\n",
    "\"\"\")"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Given the string text = \"Python is amazing\", write a program to extract and print the \n",
    "word \"amazing\" from it."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      " amazing\n"
     ]
    }
   ],
   "source": [
    "text = \"Python is amazing\"\n",
    "print(text[9:])"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "challenge: Concatenate two strings, first_name and last_name, with a space in between, and \n",
    "print the full name in uppercase"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 40,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "ABDALLAH AYMAN\n"
     ]
    }
   ],
   "source": [
    "first_name=\"abdallah\"\n",
    "last_name=\"ayman\"\n",
    "print(first_name.upper() +\" \"+ last_name.upper() )"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Write a program to calculate the area of a rectangle with a width of 5 and a height of \n",
    "10."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 42,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "The area of the rectangle is: 50\n"
     ]
    }
   ],
   "source": [
    "width = 5\n",
    "height = 10\n",
    "area = width * height\n",
    "print(\"The area of the rectangle is:\", area)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    ": Create two numbers, a = 20 and b = 7, and print the result of each arithmetic \n",
    "operation: addition, subtraction, multiplication, division, and modulo."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 44,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Addition: 27\n",
      "Subtraction: 13\n",
      "Multiplication: 140\n",
      "Division: 2.857142857142857\n",
      "Modulo: 6\n"
     ]
    }
   ],
   "source": [
    "\n",
    "a = 20\n",
    "b = 7\n",
    "\n",
    "\n",
    "addition = a + b\n",
    "print(\"Addition:\", addition)\n",
    "\n",
    "\n",
    "subtraction = a - b\n",
    "print(\"Subtraction:\", subtraction)\n",
    "\n",
    "\n",
    "multiplication = a * b\n",
    "print(\"Multiplication:\", multiplication)\n",
    "\n",
    "\n",
    "division = a / b\n",
    "print(\"Division:\", division) \n",
    "\n",
    "\n",
    "\n",
    "modulo = a % b\n",
    "print(\"Modulo:\", modulo)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Create a list of five of your favorite foods. Print the entire list, then print the third \n",
    "item in the lis"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 45,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "['burger', 'pasta', 'sushi', 'pizza', 'ice cream']\n",
      "sushi\n"
     ]
    }
   ],
   "source": [
    "foods = [\"burger\", \"pasta\", \"sushi\", \"pizza\", \"ice cream\"]\n",
    "\n",
    "print(foods)\n",
    "print(foods[2])\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    " Convert the list into a tuple, and try to change the first item in the tuple. Observe \n",
    "and explain the result."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 48,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "('burger', 'pasta', 'sushi', 'pizza', 'ice cream')\n"
     ]
    }
   ],
   "source": [
    "\n",
    "foods = [\"burger\", \"pasta\", \"sushi\", \"pizza\", \"ice cream\"]\n",
    "favorite_foods_tuple = tuple(foods)\n",
    "\n",
    "print(favorite_foods_tuple)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Given the string sentence = \"Learning Python is fun!\", write a program to slice and \n",
    "print the word \"Python\" from it"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      " Python\n"
     ]
    }
   ],
   "source": [
    "s = \"Learning Python is fun!\"\n",
    "\n",
    "print(s[8:15])\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    " Replace the word \"fun\" with \"awesome\" in the sentence and print the new \n",
    "sentence"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      " Python\n",
      "Learning Python is awesome!\n"
     ]
    }
   ],
   "source": [
    "s = \"Learning Python is fun!\"\n",
    "\n",
    "\n",
    "new_s = s.replace(\"fun\", \"awesome\")\n",
    "print(new_s)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Create a dictionary called student with the keys name, age, and grade. Assign values \n",
    "to each key and print the dictionary"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Alice\n",
      "{'name': 'Alice', 'age': 15, 'grade': 10, 'city': 'New York'}\n"
     ]
    }
   ],
   "source": [
    "student = {\n",
    "    \"name\": \"Alice\",\n",
    "    \"age\": 15,\n",
    "    \"grade\": 10\n",
    "}\n",
    "\n",
    "print(student[\"name\"])\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Add a new key city to the dictionary and set it to any city name. Print the \n",
    "updated dictionary.\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "student = {\n",
    "    \"name\": \"Alice\",\n",
    "    \"age\": 15,\n",
    "    \"grade\": 10\n",
    "}\n",
    "\n",
    "print(student[\"name\"])\n",
    "student[\"city\"] = \"New York\"\n",
    "\n",
    "print(student)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Write a program that takes two numbers from the user and prints their sum, \n",
    "difference, product, and division result.\n",
    "Challenge: Use the modulo operator to check if the first number is divisible by the second \n",
    "number, and print the result as \"Divisible\" or \"Not Divisible\""
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": [
    "num1 = float(input(\"Enter the first number: \"))\n",
    "num2 = float(input(\"Enter the second number: \"))\n",
    "\n",
    "sum = num1 + num2\n",
    "difference = num1 - num2\n",
    "product = num1 * num2\n",
    "division = num1 / num2\n",
    "\n",
    "print(\"Sum:\", sum)\n",
    "print(\"Difference:\", difference)\n",
    "print(\"Product:\", product)\n",
    "print(\"Division:\", division)\n",
    "\n",
    "if num1 % num2 == 0:\n",
    "    print(\"Divisible\")\n",
    "else:\n",
    "    print(\"Not Divisible\")"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.12.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
