# Introduction to the Array in Javascript #36 | Javascript Course

In programming, quite often we will need an ordered collection, where we have a first, second, third, and so on. For example, we need that to store a list of something: users, items, elements, etc.

There exists a special data structure named ``Array``, to store ordered collections.

## Declaration
This is how we declare an array; the most important part here are the square brackets:

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

An array can store elements of any type:

```const arr = [ 'LCO', { name: 'Hitesh' }, true, function() { alert('hello'); } ];```

You're often going to find yourself needing to loop through all the elements of an array. That's where the for loop we've learned comes in handy:

```
for (let i = 0; i < months.length; i++) {
	console.log(carr[i]);
}
```

Later, I've dedicated a few whole lectures about different built in array methods for looping. They allow us to loop faster, with added functionality and less code.

Timestamps:-

00:00-2:02 (Introduction to Arrays)
2:03-4:37 (How to write an array)
4:37-7:24 (Things to remember)
7:25-8:15 (Conclusion)

Get the code:- https://github.com/hiteshchoudhary/

Got some doubts and want to ask?, join :-
https://hitesh.ai/discord

Instagram:- https://www.instagram.com/hiteshchoudharyofficial/

Thank you for joining.
