## Numbers
Numbers are a basic class.  Numbers are basic objects.  Ruby can act like any calculator on numbers

## Arithmetic
We use the common operators for addition, subtraction, multiplication, and division.  Let's see how our Ruby calculator works:
```ruby
 2+3 #=> 5
 3*9 #=> 27
 14-7 #=> 7
 21/7 #=> 3
 9%4 #=> 1
 ```
 The last example is called the modulus which gives the remainder of a division problem.  9 divided by 4 is 2 with a remainder of 1.  Modulus returns the reaminder which is 1.
 
## Kinds of Numbers
There are two kinds of numbers:
  * Fixnum -- Whole numbers
  * Float -- numbers with decimals
These two different kinds of numbers interact well together when it comes to arithmetic.
```ruby
2 + 3.3 #=> 5.3 
7.4 - 3.4 #=> 4.0
2.2 * 4 #=> 8.8
9.7/3 #=> 3.233333333333333
```
## Methods
* to_i -- changes a float to an integer (rounds down)
```ruby
4.6.to_i #=> 4
4.1.to_i #=> 4
```
* to_s -- changes a number to a string
```ruby
456.to_s #=> "456"
57.3.to_s #=> "57.3"
```
* .even? -- returns true or false depending on whether a number is even or not
* .odd? -- returns true or false depending on whether a number is odd or not
```ruby
57.odd? #=> true
57.even? #=> false
```


##To Learn More
http://ruby-doc.org/core-2.1.1/Integer.html
