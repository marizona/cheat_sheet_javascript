##The apply() 

The method calls a function with a given 'this' value, 
and arguments provided as an array (or an array-like object).

->  const numbers = [5, 6, 2, 3, 7];
    const max = Math.max.apply(null, numbers);
    console.log(max);
    // expected output: 7


