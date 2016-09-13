## Coding Ruby

### Variables

This is a `variable`. Keep typing.

Variables can be assigned values manually.
```
apples = 10
boxesfull = true
cat = 'meow'
```
Variables can be used for storing values in expressions and also for methods.

In this expression '15' would be returned or displayed.
```
a = 10
b = 5
return a + b
```
Variables can be many things, such as strings, integers, booleans, and arrays.
```
string = 'text'
integer = 2
boolean = false
array = [1, "hi", true]
```
### Conditionals

In ruby, booleans represent true and false, and can be used in many conditional statements. Two of the most common statements you will use are if statements and while loops.

If statements evaluate whether or not a certain statement is true or false. If the statement is true the code in the if statement will run.
```
if(2 < 3)
  return '3 is greater than 2'
end
```
In this case the code would run because 3 is greater than 2.

In the case that the code doesn't run for some reason, we can use else to make something else happen.
```
if(5 == 3)
	return "Hi"
else 
	return "Bye"
end
```
This time the code would return "Bye", because the initial condition isn't true. If it were to say, 5 == 5, then only the first condition would return true.

Another type of conditional method is a while loop. A while loop will only run while the predetermined condition is true. 

```
x = 0
while(x < 5)
	x = x + 1
end
```
This code would run for 5 times since it would take 5 times to run it before the condition is no longer true.
```
def my_method(a)
  a + 10
end
```
