# Methods

Methods are like verbs in English.  The act on objects.  Many methods already exist in Ruby.  But you can also create your own methods.

## Creation

Methods are created by using the keyword "def" and then giving def a name, kind of like a variable.  Then you write your functionality after the new method name and close the whole thing with the keyword, end.  Check out an example:

```ruby
def greeting
puts "Hey there"
end  #=>"Hey there"
```
## Some Existing Methods

Some common methods are:
* puts = put string.  Prints a string to the screen.
* gets = get string.  Gets a string from a user's input
* .length = counts the number of characters in an array or string for example.

## Arguments
Methods can have information passed into them called arguments.  Arguments are passed into methods using parentheses immediately following the method.  In the example below a and b are the arguments.  The real values in this example are that a and b = 3 and 5 respectively.
```ruby
def add(a, b)
  puts a + b
end
add(3,5)
#=> 8
```
## Calling a method
In order to invoke the functionality of a method, you "call" it.  You call a method by simply typing its name.  In the example below, the last line of the method is "add(3, 5)".  That is the method call and 3 and 5 are the arguments being passed into the method.
```ruby
def add(a, b)
  puts a + b
end
add(3,5)
#=> 8
```


##To Learn More
http://ruby-doc.org/core-2.2.0/Method.html
