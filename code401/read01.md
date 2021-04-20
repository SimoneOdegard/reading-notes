# Read 01

1. **Describe (in plain English) what ```Array.map()``` does:** .map creates a new array for you. It will give you the same amount of items in your new array as the original array. Your original array will not be modified. It will call a function (a callback) on each item in the original array that you map through. Each indivdual result that you receive from the items you map through will be your results in your new array.

[link](https://www.youtube.com/watch?v=erLq0zb01y4)

2. **Describe (in plain English) what ```Array.reduce()``` does:** .reduce will run through an array. It will call a function (a callback) on each item in the original array. In addition to receiving the value and index (a place in the array), it will also receive an accumulator which is placeholder for what will be your result when .reduce is done running. An accumulator can be any type (object, string, number, array).

[link](https://www.youtube.com/watch?v=_uICFozlNYE)

3. **Provide code snippets showing how to use ```superagent()``` to fetch data from a URL and log the result:**
```
function getCharacters (){
  return superagent.get('https://swapi.dev/api/people/');
}
```

3. **With normal Promise ```.then()``` syntax:**

```
function getCharacters (){
  superagent.get('https://swapi.dev/api/people/')
  .then( data => {
    let newArray = [];
    let results = data.body.results;
    for (let i = 0; i < results.length; i++){
      newArray.push({[results[i].name]: results[i].url});
    }
    console.log(newArray);
  })
  .catch(err => console.error(err));
}
```

3. **Again with ```async``` / ```await``` syntax:** Async is saying load everything else, then load me while await will take time to load. Await says "I promise I will get this info".

```
async function getCharacters (){
  let data = await superagent.get('https://swapi.dev/api/people/');
  let newArray = [];
  let results = data.body.results;
  for (let i = 0; i < results.length; i++){
    newArray.push({[results[i].name]: results[i].url});
  }
  console.log(newArray);
}
```

4. **Explain promises as though you were mentoring a Code 301 level student:** Promises are a method of doing asynchronous programming with JavaScript. Promises are functions that you call that will return at a later point. It will run out of the normal flow. A promise is like saying "run everything else, and I promise I will get back to you with my answer."

[link](https://www.youtube.com/watch?v=4bPdjAerRzQ)

5. **Are all callback functions considered to be Asynchronous? Why or Why Not?:** No, all callback functions are not asynchronous. The following methods perform callbacks synchronously: ```forEach```, ```map```, ```filter```, ```reduce```

[link](https://dev.to/marek/are-callbacks-always-asynchronous-bah)

[<== Back](https://simoneodegard.github.io/reading-notes/)