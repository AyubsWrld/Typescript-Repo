# Enum 
- Similar to how enums work within other programming languages . Data structure which holds multiple different symbols incrementing from 0 or if the user wants from a starting `idx`


```typescript
enum Errors { 
    TYPE_ERROR, // 0
    TYPE_ERROR, // 1
    TYPE_ERROR, // 2
    TYPE_ERROR, // 3
}
```

# User delineated starting point 

```typescript
enum Errors { 
    TYPE_ERROR,  = 1
    TYPE_ERROR, // 2
    TYPE_ERROR, // 3
    TYPE_ERROR, // 4
}
```
