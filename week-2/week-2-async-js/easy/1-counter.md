## Create a counter in JavaScript
const count = (n) => {
  let counter = 0;
  for(let i = 0; i <= n; i++) {
    counter++;
  }
  return counter;
}
console.log(count(7));
We have already covered this in the second lesson, but as an easy recap try to code a counter in Javascript
It should go up as time goes by in intervals of 1 second
