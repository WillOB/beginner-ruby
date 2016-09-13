# beginner-ruby
# The basics of Ruby

## Variables.

#### How to assign a **variable**:
```
x = 5.to_i
str = 'hello'
```
Creates a variable x and sets equal to integer 5, creates a variable str and sets equal to string 'hello'.
The `.to_i` makes the 5 an integer value.

#### How to use a **variable**
`return str`

This will return 'hello,' as we previously set it to 'hello.'

You can also do math with integer strings:
`x + 5`
This will equal 10.

## Conditionals

#### Writing if statements
```
if 5 > 2
  return 'yes'
end
```
This will only return yes if 5 is greater than two.

```
if 10 > 20
  return 'yes'
else
  return 'no'
end
```
This will return no, as 20 is always greater than 10.
```
if x == 5
  return 'hi'
elsif x == 2
  return 'bye'
else
  return 'elephant'
```
The `elsif` used here says "If x is not 5 but it is two, return 'bye'"
