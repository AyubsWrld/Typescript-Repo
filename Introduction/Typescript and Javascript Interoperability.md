# Interoperability 
- We can utilize **Typescript** code within **Javascript** files and vice versa . 
- To utilize **Typescript** within **Javascript** we need to run it through a Transpiler (`tsc`) 

## @ts-check 

- **Typescripts** compiler also allows for type checking for plain javascript code by using the `// @ts-check` comment at the top of a file . This allows the compiler to validate types by inspecting the JSDoc comments

```javascript
// @ts-check
/**
* Adds two numbers 
* @param { number } a - The first number 
* @param { number } b - The second number
* @returns { number } the sum of the two numbers 
*/

function add( a , b)
{
     return a + b ; 
}
```

#ts-config
