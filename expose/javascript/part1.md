# Part 1. A Quick Introduction...

1. Line 9 prints 
```
values added: 20
```

2. Line 13 prints 
```
final result: 20
```

3. Line 9 prints  
```
values added: 20
```

4. Line 13 returns an error since the variable `result` is defined in a particular block (line 13 is not in it) with a keyword `let`. 

5. Line 9 returns an error since the keyword `const` prevents the variable `result` being reassigned after it is assigned to `0` at line 5. 

6. Line 13 returns an error since the keyword `const` gives the variable `result` the same scope as the keyword `let`, which cannot be accessed on line 13. 

