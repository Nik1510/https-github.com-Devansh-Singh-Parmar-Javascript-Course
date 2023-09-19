# JavaScript Mein Array Ki Introduction #36 | JavaScript Course

Programming mein, humare paas aksar aise ordered collection ki zaroorat hoti hai, jahan pe humare paas ek pehla, doosra, teesra, aur aage aise chizon ki list hoti hai. For example, humein kuch store karne ki zaroorat hoti hai: users, items, elements, etc.

Ek khaas data structure hota hai jiska naam hai "Array," jo ordered collections ko store karne mein madad karta hai.

## Declaration
Yeh hai humara array declare karne ka tareeka; yahan par sabse important hissa square brackets hote hain:

```const months = [ 'January', 'February', 'March', 'April' ];```

Array ke elements ko numbers se number kiya jata hai, jahan pe zero se shuru hota hai.
Hum square brackets mein uske number se ek element ko nikal sakte hain:

```console.log(months[0]); // 'January'```

Hum ek element ko replace bhi kar sakte hain:

```months[2] = 'Not March'; // [ 'January', 'February', 'Not March', 'April' ]```

...ya phir ek naya element array mein add kar sakte hain:

```months[4] = 'May'; // [ 'January', 'February', 'March', 'April', 'May' ]```

Array mein elements ki total count uska length hota hai.

```console.log(months.length); // 5```

Ek array kisi bhi type ke elements ko store kar sakta hai.

```const arr = [ 'LCO', { name: 'Hitesh' }, true, function() { alert('hello'); } ];```

Aapko aksar zaroorat padegi ki aap array ke saare elements par loop chalayein. Yahan pe wo for loop ka istemal aata hai jo humne seekha hai:

```
for (let i = 0; i < months.length; i++) {
	console.log(carr[i]);
}
```

Mere lectures ke dauraan, maine various built-in array methods ke baare mein baat ki hai jo faster looping enable karte hain, additional functionality provide karte hain, aur kam code require karte hain. Iske alawa, maine arrays ke basics ke baare mein bhi baat ki hai, jaise ki unhe kaise likha jata hai aur important considerations kya hain.

Har section ke liye timestamps kuch is tarah se hain:

00:00-2:02: Arrays Ki Introduction

2:03-4:37: Array Kaise Likhein

4:37-7:24: Important Considerations

7:25-8:15: Conclusion

🖥️🧾 Agar aap code ki interested hain, to aap use yahan par https://github.com/hiteshchoudhary/ mein find kar sakte hain. 

Agar aapke paas koi sawal ya shanka hai, to humare saath judne ke liye aap https://hitesh.ai/discord par aa sakte hain.

Aap mujhe Instagram par bhi follow kar sakte hain: https://www.instagram.com/hiteshchoudharyofficial/.

Thank you for attending!
