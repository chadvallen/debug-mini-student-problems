Problem:
```
Line 17:  Expected an assignment or function call and instead saw an expression  no-unused-expressions
```

Where:
line 17 - no return 

Fix:
add return and wrap div in parentheses
```
{letters.map((letter, i) => {
          return(<div key={i}>
            {letter}
          </div>)
        })}
```
