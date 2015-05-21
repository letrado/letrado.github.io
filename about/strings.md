# Strings

Strings are objects which are enclosed in in quotation marks

## Creation

You create strings by typing text between quote marks.
```ruby
"Stringy" #=> "Stringy"
```
A string can be initialized surrounded by either double quote or single quote characters.

## Methods

Here are some methods you can use on strings:
```ruby
String.new("Here is a new string.") #=> "Here is a new string."
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
"I am writing " + "a string." #=> "I am writing a string."
```
You can also multipy strings, like this:
```ruby
"repeat " * 4 #=> "repeat repeat repeat repeat "
```

## Special Properties

###Interpolation

You can insert objects like variables into strings, like in the example, it is called interpolation.
```ruby
name = "Mark"
food = "Chinese"
"#{name} wants #{food} for dinner." #=> "Mark wants Chinese for dinner."
```
###Escape Characters

If you use the \ character in a string, it "escapes", or ignores the character after it.  So if you try to use before the # sign in the example above, it will prevent interpolation.
```ruby
"#\{name} wants \#{food} for dinner." #=> "\#{name} wants \#{food} for dinner."
```
You can also use escape t for the tab function in formatting as well as for the n for a new line like this:
*  "\t\t\t"  will tab three times
*  "\n" will creat a new line.

###Accessing Elements

You can access characters in a string like this by passing it an index number much like in an array.
```ruby
"groove is in the heart"[4] #=> "v"
"platypus"[-1] #=> "s"
"code school is fun"[0] #=> "c"
```

##To Learn More
http://ruby-doc.org/core-2.2.0/String.html
