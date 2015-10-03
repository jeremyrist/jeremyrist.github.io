##**ARRAYS**##

####_An array is like one row of chairs in this classroom_.####

![img](http://www.niemanlab.org/images/lecturecc.jpg)

###What are we going to learn?###
* How to remove the last element in an array.

###Why?###
* Because arrays are most useful for storing data and when you store data it's also nice to be able to retrieve that data so you can display it or do whatever you need to do to it.

###How do we do this?###
The **`pop()`** method will help you do this!

####Steps:####
1. Define your array.
      `var goodRap = ["Action Bronson", "Curren$y", "Kanye West", "Kendrick Lamar", "Meek Mill"];`

      _(In this example `var` stands for `variable` and `goodRap` is the name of the variable. The equals sign and square brackets let you know that what is inside the square brackets will be an array. The strings in the quotation are referred to as `elements`.)_
      
2. Then use the `pop()` method to retrieve the last element. 

      `goodRap.pop();`
      
3. This will remove the string `"Meek Mill"`, which is good because he does not belong in this particular array. Fuckouttahere.

4. Now the result of `goodRap` will be:
      `Action Bronson, Curren$y, Kanye West, Kendrick Lamar`

####Fun Fact!####
* The `shift()` method is the exact opposite of the `pop()` method, it returns the first item.

And there you have it.. that's how you take out the last element of an array. POP POP!
