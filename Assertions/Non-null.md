# Non-null assertions 

- (`!`) assertion tells the compiler that a value will never be null or undefined 

```typescript
let name : string | null = null ; 

let nameLength = name!.length // this should never be null 

```

