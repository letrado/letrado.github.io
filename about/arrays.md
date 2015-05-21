## Arrays
Arrays are collections of data.  Elements of an array can be strings, numbers, and even hashes.

## Array Creation
You create an array by typing square brackets [] and placing the objects inside the brackets.  The individual objects in an array are separated by commas.  Below is an example.

```ruby
array = [1, 2, 3, 4, 5] #=> [1,2,3,4,5]
```

## Accessing Items in an Array
Items in an array are indexed starting with zero.  So the first item in the array is 0, the second item is 1, the third item is 2, and so on.  
If you want to access an item in an array, you reference its index number inside square brackets next to the name of the array.  Check out the example below:

```ruby
veggies = ["squash", "peas", "carrots"]
veggies[2] #=> "carrots"
```

### Arithmetic 
Arrays can be added together.  Observe using the arrays from our two previous arrays:
```ruby
veggies + array #=> ["squash", "peas", "carrots", 1, 2, 3, 4, 5]
```

## Some useful methods to use on arrays.
* .push -- adds to an array
* .pop -- takes away from an array and changes the array to what is left
* reverse -- reverses the order of the objects in the array

Here are these methods in use:
```ruby
veggies.push("corn") #=> ["squash", "peas", "carrots", "corn"]
veggies.pop(2) ["carrots", "corn"]
```
After .pop our veggies array is now only left with:
```ruby
veggies #=> ["squash", "peas"]
```
Here is .reverse in action
```ruby
furniture = ["couch", "table", "chair"] #=> ["couch", "table", "chair"]
furniture.reverse #=> ["chair", "table", "couch"]
```


##To Learn More
http://ruby-doc.org/core-2.2.0/Array.html
