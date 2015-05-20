# Strings

Strings are objects which are enclosed in in quotation marks

## Creation

You create strings by typing text between quote marks.
```ruby
"Stringy" #=> "Stringy"
```
or by passing the characters (in quotes) to String.new
```ruby
other_string = String.new("as thus")
```
A string can be initialized surrounded by either double quote or single quote characters.

## Methods

Here are some methods you can use on strings:
```ruby
"Words".length #=> 5
"Words".upcase #=> "WORDS"
"WORDS".downcase #=> "words"
"string".include?("A") #=> false
"words".capitalize #=> "Words"
"1234".to_i #=> 1234
"Words".to_i #=> 0
```

## Arithmetic

You can add strings together like this:
```ruby
"I am writing" + "a string." #=> "I am writinga string."
"I am writing " + "a string." #
"Ho! Ho! Ho!" + " Merry Christmas!" #=> "Ho! Ho! Ho! Merry Christmas!"
```
## Special Properties

###Interpolation

A double-quoted string can have Ruby code embedded in it with the character sequence #{}. 
The embedded code will get evaluated and the return value inserted into the string.
```ruby
"8 * 9 = #{8 * 9}" #=> "8 * 9 = 72"
name = "Bob"
"Hi there #{name}" #=> "Hi there Bob"
```
###Escape Characters

The \ character can be used to change the meaning of the character following it in a (double-quoted) string.
* `\n` is a `newline`
* `\t` is a `tab`
* `\#{}` prevents interpolation

###Accessing Elements

Characters in a string can be accessed with [] characters, similar to an array.
```ruby
"the beginning"[0] #=> "t"
```

##To Learn More
http://ruby-doc.org/core-2.2.0/String.html
