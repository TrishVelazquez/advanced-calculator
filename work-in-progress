"""Math functions for calculator."""


def add(numbers):
    """Return the sum of the two inputs."""
    total_count = 0

    for each in numbers:
        total_count += each

    return total_count

#print(add([5, 6, 8, 10]))



def subtract(numbers):
    """Return the second number subtracted from the first."""
    first = numbers[0] + numbers[0]

    for each in numbers:
        first = first - each

    return first

#print(subtract([100, 10, 10, 10, 10]))

def multiply(numbers):
    """Multiply the two inputs together."""
    total = 1

    for each in numbers:
        total *= each

    return total

#print(multiply([10, 10, 2, 2]))

def divide(numbers):
    """Divide the first input by the second and return the result."""

    start_number = numbers[0] * numbers[0]

    for each in numbers:
        start_number = start_number / each

    return start_number

#print(divide([500, 100, 2]))


def square(numbers):
    """Return the square of the input."""
    squared = []

    for each in numbers:
        squared.append(each * each)
        print(each*each)

    return squared

#print(square([2, 3, 4, 5]))

def cube(numbers):
    """Return the cube of the input."""
    cubed = []

    for each in numbers:
        cubed.append(each * each * each)
        print(each * each * each)

    return cubed

#print(cube([2, 3, 5, 10]))


def power(numbers):
    """Raise num1 to the power of num2 and return the value."""
    result = numbers[0]
    exponent = 1
    #iteration = numbers[1:]

    for each in numbers[1:]:
        exponent *= each

    return result ** exponent

#print(power([2, 3, 4, 5]))

def mod(numbers):
    """Return the remainder of num1 / num2."""
    start = numbers[0]

    for each in numbers[1:]:
       new_start = start % each
       start = new_start

    return start

#print(mod([100, 85, 10, 3]))

def add_mult(num1, num2, num3):
    """Returns result of num1 and num2 and multiply the sum with num3."""
    return (num1 + num2) * num3

def add_cubes(num1, num2):
    """Returns the sum of two cubes numbers"""
    return (num1 * num1 * num1) + (num2 * num2 * num2)
