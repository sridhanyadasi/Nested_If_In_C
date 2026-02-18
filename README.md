# Nested if Statement in C

This repository is created to help beginners understand the concept of
**nested if statements in C programming** using simple explanations,
syntax, and examples.

--------------------------------------------------

## 🔹 What is a Nested if?

A **nested if** statement means placing one `if` statement inside
another `if` statement.

In simple words:
- An `if` inside another `if` is called a nested if
- The inner `if` is checked only when the outer `if` condition is true

--------------------------------------------------

## 🔹 Why Do We Use Nested if?

We use nested if statements when:
- one condition depends on another condition
- multiple levels of decision-making are required
- a single if or if-else is not sufficient

Nested if helps us write programs that can handle
**complex logical decisions**.

--------------------------------------------------

## 🔹 Uses of Nested if

Nested if statements are used when:
- checking multiple related conditions
- validating input step by step
- finding the largest or smallest number
- checking grades, eligibility, or ranges
- implementing multi-level decision logic

--------------------------------------------------

## 🔹 Syntax of Nested if

``c
if (condition1)
{
    if (condition2)
    {
        // code executes when both condition1 and condition2 are true
    }
}


How Nested if Works

First, the outer if condition is checked

If it is true, the inner if condition is checked

If both conditions are true, the inner block executes

If the outer condition is false, the inner if is skipped

🔹 Example
#include<stdio.h>

int main()
{
   int a = 10, b = 20;

  if (a < b)
    {
        if (b > 15)
        {
            printf("Both conditions are true");
        }
    }

   return 0;
}

Flow chart for Nested - If  Statement
              ┌───────────────┐
              │    Start      │
              └───────┬───────┘
                      │
                      ▼
              ┌────────────────┐
              │  Condition 1 ? │
              └───────┬────────┘
              Yes     │        No
                      │
              ▼       │
      ┌────────────────┐       ┌───────────────┐
      │  Condition 2 ? │       │     End       │
      └───────┬────────┘       └───────────────┘
      Yes     │        No
              │
      ▼       │
┌──────────────────────┐
│ Execute Inner Block  │
└──────────┬───────────┘
           │
           ▼
     ┌───────────────┐
     │     End       │
     └───────────────┘


🎯 Purpose of This Repository

To understand nested if statements clearly

To learn multi-level decision making

To practice conditional logic in C

To build a strong foundation for advanced control structures

👤 Author

Sri Dhanya
