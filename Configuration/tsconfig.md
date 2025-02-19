# Purpose
- The `tsconfig.json` file contains the specifications for which the **Typescript Compiler** will operate on . Think of it as the make configurations for a **Typescript** file . 

# Specifications


target: the version of JavaScript to compile to.
module: the module system to use.
strict: enables/disables strict type checking.
outDir: the directory to output the compiled JavaScript files.
rootDir: the root directory of the TypeScript files.
include: an array of file/directory patterns to include in the compilation.
exclude: an array of file/directory patterns to exclude from the compilation.
Given below is the sample tsconfig.json file:


```json 
{
  "compilerOptions": {
    "target": "es5",
    "module": "commonjs",
    "strict": true,
    "outDir": "./dist",
    "rootDir": "./src",
  },
  "exclude": ["node_modules"],
  "include": ["src"]
}
```

# Note

These speicifications can be passed in via the CLI aswell as flags

```bash
tsc --target ES5 --module commonjs
```



