# Intersection Types
- Combines multiple different types into a single type and is done through the use of ( `&` ) operator .


```typescript

type typeA =  {
    age : number ,
}

type typeB =  {
    name : string ,
}

type AB = typeA & typeB ; 

```
