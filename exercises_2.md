# Exercises 2

## Loop practice

I recommend writing sudo code for each of these.

Don't alter old code. Write out each of these answers in their entirety. Rewrite them when instructed to solve using a different tool. This is to get your fingers moving more and cause you to think about small syntax decisions as you write them a second time.

1. Start with an array of numbers. Collect all the numbers over 50 and print them to the terminal after the loop is complete. Start with this loop.
   
   ```numbers = [39, 152, 44, 1, 55, 55, 42, 90, 5]```
2. Access a character from a string using an index. Pull the letter "r" out of the string "hammerhead" and print it to the terminal.
3. Concatenate two strings together and print them to the terminal. (Note: you can add spaces with another string.)
   
    ```first_word = "jump"```

    ```second_word = "to"```

    ```third_word = "conclusions"```

4. Use a times loop to build a string from an array. (aka. don't use `join` method) Start with this array. (remember that `x = x + 1` is the same as `x =+ 1`)
   
   ```letters = ["t", "h", "e", "y", " ", "c", "h", "a", "n", "g", "e", "d", " ", "t", "i", "m", "e", "z", "o", "n", "e", "s", "?", "!"]```

   the result should be `"they changed timezones?!"` printed to the terminal.
5. Use an `each` loop to do the same problem again.
6. Take out the vowels. Build a new string with an times loop. Iterate over each letter in the string.
7. Take out the vowels with an each loop. (Note: that this requires you to first convert the string into an array with another times loop or the `split` method, your choice - it's the same thing under the hood. This is an example of how a times loop is the better choice to solve the "take out the vowels" problem, but it's important to see how each way solved the problem. If possible, don't convert the data to a new form if it's going to return in the same form. aka. starts as a String and ends as a String)

## Hashes

Reminder that Arrays are better for a list of similar type objects (a list of strings, a list of numbers, a list of cars objects - oh, too soon?). Arrays are a better choice when the values are unnamed and order matters. Hashes are a better structure if you have named values (first_name, last_name, zip_code, etc.) which means that you can't duplicate that role. such as two `first_name` keys are not possible in a hash. And order is not an absolute in a hash, sometimes things move around.

1. Create a hash with 3 key value pairs
2. Read from a hash, By calling their keys one at a time, print each value on a separate line.
3. Add a key to a hash. Add 2 new keys to the original hash after it was defined. then print the entire hash using `p` keyword.
4. Print a string interpolated with values from a hash.
   
   ```apartment = { num_of_rooms: 2, sq_ft: 1000, agent: "Christina Hendricks"}```

   result: print `Christina Hendricks is showing a 1000 square foot apartment with 2 bedrooms.`

   (Reach goal: add another key representing that the apartment has an in unit washer/dryer and stored as a boolean. Then add that information to the string without printing the words `true` or `false`. You decide how to add the text of `and has an in unit washer/dryer` to your message before printing it.)