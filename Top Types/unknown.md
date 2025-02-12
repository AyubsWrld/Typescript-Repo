# Unknown
- Typesafe counterpart of any . Use for when that specific value is uknown in some portion of the code . This makes it so that operations cannot be done on unknown until it is set to any or some definite datatype

```typescript

let testValue : unknown ; 

function testType( testValue : unknown ) : void {
    testValue.doSomething() ; // throws an error
}
```
