# Introduction to the Array in Javascript #36 | Javascript Course

In programming, we often need an ordered collection, where we have a first, second, third, and so on. For example, we require that to store a list of something: users, items, elements, etc.

There exists a special data structure named ``Array``, to store ordered collections.

## Declaration
This is how we declare an array; the most important part here is the square brackets:

```const months = [ 'January', 'February', 'March', 'April' ];```

Array elements are numbered, starting with zero.
We can get an element by its number in square brackets:

```console.log(months[0]); // 'January'```

We can replace an element:

```months[2] = 'Not March'; // [ 'January', 'February', 'Not March', 'April' ]```

...or add a new one to the array:

```months[4] = 'May'; // [ 'January', 'February', 'March', 'April', 'May' ]```

The total count of the elements in the array is its length.

```console.log(months.length); // 5```

An array can store elements of any type.

```const arr = [ 'LCO', { name: 'Hitesh' }, true, function() { alert('hello'); } ];```

You're often going to find yourself needing to loop through all the elements of an array. That's where the for loop we've learned comes in handy:

```
for (let i = 0; i < months.length; i++) {
	console.log(carr[i]);
}
```

During my lectures, I discussed various built-in array methods that enable faster looping, provide additional functionality, and require less code. Additionally, I covered the basics of arrays, including how to write them and important considerations to keep in mind. 

The timestamps for each section are as follows: 

00:00-2:02: Introduction to Arrays
2:03-4:37: How to Write an Array
4:37-7:24: Important Considerations
7:25-8:15: Conclusion

🖥️🧾 If you're interested in getting the code, you can find it at https://github.com/hiteshchoudhary/. 

If you have any questions or doubts, feel free to join us at https://hitesh.ai/discord.
You can also follow me on Instagram at https://www.instagram.com/hiteshchoudharyofficial/. 

Thank you for attending!
