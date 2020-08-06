# Break Down Problems, Build Up Solutions

## Break down problems into smaller, simpler problems w/ less moving parts

## Build up solutions, bit by bit and piece by piece to solve those smaller problems

## Build up your verbs as layers of a pyramid
- Our simplest verbs are operators. They are verbs that work on nouns and give us back a new noun.
    - `+` adds two numbers and returns a new number..
    - `-`
    - `*`
    - `/`
    - `and`
    - `not`
    - `or`
    - `in`
- Next simplest verbs are built-in functions
    - `len()`
    - `type()`
    - `sum()`
    - `max()`

- A higher layer is combining operators and built-in functions into user-defined functions

- Lather, rinse, repeat

- Your highest level function should be:

    ```
    def solve_the_entire_problem(inputs):
        result = first_part_of_problem(inputs)
        output = second_part_of_problem(result)
        return output
    ```    
- Each layer is less english more code (from outside in)
- Each layer is more code less english (the closer you are to the bottom of the pyramid)
    
