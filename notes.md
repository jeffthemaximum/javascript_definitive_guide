### falsy values
- There's 6 of them
```
undefined
0
-0
NaN
""
null
```

### global object
- In top level js code that is not part of a function, `this` refers to the global object.
- In browser code, `window` refers to the global object, and `window` also defines a few other globals.
- If your code defines global vars, then the global object holds those variables.
