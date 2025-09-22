# ES6 Concepts

## 1) Difference between var, let, and const  
In JavaScript, `var`, `let`, and `const` are all used to declare variables but they don’t work the same way. `var` is the older one, it is function-scoped and can be re-declared multiple times. The problem is, `var` gets hoisted, which often creates confusion. `let` and `const` came in ES6. Both of them are block-scoped, meaning they only work inside the block where they are written. With `let` you can change the value later, but you cannot declare the same variable name twice in the same block. `const` is stricter, once you set a value you cannot reassign it. However, if it’s an object or array, the contents can still be changed.

## 2) Difference between map(), forEach(), and filter()  
These three methods look similar but their purposes are different. `map()` is used when you want to transform each element of an array and get a brand-new array with the changed values. `forEach()` just runs a function for every element but doesn’t return anything, it’s usually used for things like printing or updating. `filter()` is used to pick out only the elements that match a condition and it also returns a new array. So, `map` is for transformation, `forEach` is for looping through, and `filter` is for selection.

## 3) Arrow functions in ES6  
Arrow functions are a shorter way to write functions in ES6. They use the `=>` symbol and are very handy when writing simple or one-line functions. The main difference from normal functions is that arrow functions don’t have their own `this` value; they use the `this` from the outer scope. This makes them useful when working with callbacks or when you want cleaner code.

## 4) Destructuring assignment in ES6  
Destructuring is a feature that lets you pull values out of arrays or objects and store them in variables in a neat way. For example, instead of writing `person.name` and `person.age` again and again, you can just extract them directly in one line. The same goes for arrays: instead of accessing items with indexes, you can assign them to variables right away. It makes the code shorter and easier to read.

## 5) Template literals in ES6  
Template literals are strings written with backticks (`` ` ``) instead of quotes. The special thing about them is that you can put variables inside the string using `${ }` without breaking the flow. This is easier than joining strings with the `+` operator. Another benefit is that template literals support multi-line text directly, so you don’t need to add `\n` for new lines. Overall, it’s a cleaner and more modern way to work with strings compared to traditional concatenation.
