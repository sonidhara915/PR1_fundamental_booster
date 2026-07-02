# Interactive Personal Data Collector — Overview

This document explains what `fundamental_booster.py` does, without showing the underlying code.

## Purpose

The script is a simple, beginner-friendly command-line program that collects a few pieces of personal information from a user, then displays it back to them along with some behind-the-scenes details about how Python stores that data.

## What Happens When You Run It

1. **Welcome message** — the program greets the user with an introductory line.
2. **Data collection** — the user is asked to enter, in order:
   - Their name
   - Their age
   - Their height (in meters)
   - Their favorite number
3. **Summary display** — each piece of information is printed back to the user, along with:
   - Its **data type** (e.g. text, whole number, decimal number)
   - Its **memory address** — a low-level identifier showing where that value lives in the computer's memory during this run
4. **Birth year estimate** — the program calculates an approximate birth year by subtracting the user's age from a fixed reference year (2026).
5. **Closing message** — the program thanks the user and says goodbye.

## Purpose & Use Case

This script isn't meant to be a polished, production tool — it's an educational exercise. It demonstrates several core programming concepts:
- Taking input from a user
- Converting text input into numbers
- Formatting output with embedded variables
- Inspecting the type and identity of values at runtime
- Doing basic arithmetic with variables

## Things to Keep in Mind

- **No error checking**: if the user types something unexpected (like letters where a number is expected), the program will stop with an error instead of asking again.
- **Fixed reference year**: the birth year calculation always assumes it's 2026, so it isn't automatically updated for future years.
- **Approximate results**: the birth year is only an estimate, since it doesn't account for whether the user's birthday has already happened this year.
- **Memory addresses vary**: the "memory address" shown each time is specific to that particular run of the program and will be different the next time it's executed.

## Who This Is For

Useful as a teaching example for people learning:
- How to collect and process user input in Python
- The difference between data types (text, whole numbers, decimals)
- How variables and object identity work under the hood

## Explanation video 
- https://drive.google.com/file/d/1B1kvL9F23uqYu1VgMjVPnXbYaAg6pevx/view?usp=drive_link

##For connection.
- linkedin id = www.linkedin.com/in/dhara-kondhiya-278893411
- mail id = sonidhara915@gmail.com

