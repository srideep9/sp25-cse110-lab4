1. Line 9 prints "values added: 20".
2. Line 13 prints "final result: 20".
3. You should not use var because var has function scope and could lead to a bunch of naming and scoping issues.
4. Line 9 prints "values added: 20". (The code does error afterward).
5. Line 13 does not print anything and errors saying "result is not defined". This is because a let variable has block scope, and therefore, result is not defined outside the if block.
6. Line 9 does not print anything because the code errors on line 7 since we are trying to reassign a value to a const variable.
7. Line 13 also does not print anything because the code errors on line 7 since we are trying to reassign a value to a const variable.