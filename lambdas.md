# Lambdas
## What are they?

To put it simply, lambdas are one-line functions.

To make a lambda, write:

`[funcname] = lambda [parameters]: [expression]`

(Words in brackets are replaced)

## What do they do?

Example:

```add_one = lambda x: x + 1
add_one(2) # Would say 3```

To write

`z = lambda x: y`

Would be to write

`def z(x):`
`    return y`

## Use

Lambdas are mostly used as functional arguments.

`['bar', 'spam', 'foo'].sort(key=**lambda x: x[-1]**)`

This is because they are not usually assigned to variables.

Any named lambdas should be replaced with a simple function.
