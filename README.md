# Python-Utility-Module
Using various functions to perform specific tasks.
# utility.py

def is_even(num):
    """Check if a number is even"""
    return num % 2 == 0


def calculate_square(num):
    """Return square of a number"""
    return num * num


def format_name(name):
    """Format a name in title case"""
    return name.strip().title()


def celsius_to_fahrenheit(celsius):
    """Convert Celsius to Fahrenheit"""
    return (celsius * 9/5) + 32


def count_words(text):
    """Count words in a string"""
    return len(text.split())


def save_to_file(filename, content):
    """Save content to a file"""
    with open(filename, "w") as file:
        file.write(content)
