# Learning ESLint
## Let's Learn an ESLint Rule

```
   Ok here’s how I understand this. In Javascript, semi-colons are used to separate statements but they are not mandatory.
   In most case, the Javascript engine knows where the semi-colon is supposed to go if you line-break each statement so even
   if you forgot a few semi-colons, the code can still run without an error. However, there are a few cases in which not
   having a semi-colon will cause the engine to think the next line is part of the first line statement thus breaking the code.
   The line “semi” : “error” enforces semi-colons to appear at the end of every statement. By using this, we minimize
   breaking our code due to not having semi-colons.
```


[ESLint.org](https://eslint.org/docs/latest/rules/semi-style)
