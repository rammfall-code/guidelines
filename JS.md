## Best Practices
1. Array Callback Return: Ensure callbacks used in array methods (e.g., .map, .filter) always return a value.
2. For Loop Direction: Avoid creating infinite loops by ensuring the direction of for loops is correct.
3. Getter Return: Ensure getter functions always return a value to prevent unexpected behavior.
## Error Prevention
1. No Async Promise Executor: Do not use async functions as promise executors.
2. No Await in Loop: Avoid using await inside loops, as it can cause performance issues and unexpected behavior.
3. No Class Assignment: Prevent reassigning classes after they are defined.
4. No Compare Negative Zero: Avoid comparing values to negative zero to prevent logical errors.
5. No Conditional Assignment: Disallow assignments in conditional expressions to prevent accidental assignments.
6. No Const Assignment: Prevent reassignment of const variables to maintain code integrity.
7. No Constant Condition: Avoid using constant expressions in conditions, which could lead to unintended infinite loops.
8. No Constructor Return: Prevent constructors from returning a value.
9. No Control Regex: Disallow control characters in regular expressions for better readability and fewer bugs.
10. No Debugger: Disallow the use of the debugger statement in production code.
## Duplicates and Assignment
1. No Duplicate Function Arguments: Avoid using duplicate arguments in functions, which can lead to unexpected results.
2. No Duplicate Class Members: Prevent duplicate class members from being defined in classes.
3. No Duplicate Else-If Conditions: Ensure else-if blocks don’t have duplicate conditions.
4. No Duplicate Keys in Objects: Disallow duplicate keys in object literals to avoid unexpected behavior.
5. No Duplicate Cases in Switch Statements: Prevent duplicate cases in switch statements.
6. No Duplicate Imports: Avoid multiple imports of the same module.
## Empty Statements and Unnecessary Code
1. No Empty Character Class: Disallow empty character classes in regular expressions.
2. No Empty Patterns: Prevent empty patterns in destructuring.
3. No Ex-Assignment: Avoid assigning values to exceptions in catch blocks.
4. No Fallthrough: Prevent fallthrough in switch statements.
5. No Function Assignment: Disallow reassigning functions to avoid confusion.
6. No Import Assignment: Prevent reassignment of imported bindings.
7. No Inner Declarations: Disallow function or variable declarations in nested blocks.
8. No Invalid Regex: Prevent the use of invalid regular expressions.
9. No Irregular Whitespace: Disallow irregular whitespace outside of strings and comments.
10. No Loss of Precision: Avoid loss of precision when representing numbers.
11. No Misleading Character Class: Prevent the use of misleading character classes in regular expressions.
## Object and Class Rules
1. No New Native Non-Constructor: Disallow the use of new on native non-constructor functions.
2. No Object Calls: Prevent calls to Object methods directly on objects.
3. No Prototype Built-ins: Avoid directly calling Object.prototype methods on objects.
4. No Self-Assignment: Disallow assignments where both sides of the assignment operator are the same, including properties.
5. No Self-Comparison: Prevent comparing a variable with itself.
6. No Setter Return: Ensure setters do not return values.
7. No Sparse Arrays: Disallow sparse arrays.
8. No Template Literal Strings in Regular Strings: Prevent the use of template literals inside regular strings.
9. No this Before super in Constructors: Ensure super() is called before using this in constructors of derived classes.
## Variables and Unused Code
1. No Undefined Variables: Prevent the use of undeclared variables.
2. No Unexpected Multiline: Avoid potential multiline issues in code.
3. No Unmodified Loop Condition: Disallow unmodified conditions in loops.
4. No Unreachable Code: Prevent code that will never be executed (unreachable).
5. No Unreachable Loops: Avoid creating loops that are never entered.
6. No Unsafe Finally: Prevent potentially dangerous behavior in finally blocks.
7. No Unsafe Negation: Disallow the use of ! operator to negate relational expressions.
8. No Unsafe Optional Chaining: Disallow optional chaining expressions that could cause unintended behavior.
9. No Unused Private Class Members: Prevent defining private class members that are never used.
10. No Unused Variables: Disallow unused variables in the code to keep it clean.
11. No Use Before Define: Prevent using variables before they are defined.
## Redundancy and Preferred Syntax
1. No Useless Assignment: Avoid unnecessary assignments that do not change the value.
2. No Useless Backreference: Disallow backreferences in regular expressions that will always match.
3. Require Atomic Updates: Ensure variable updates in asynchronous code are atomic.
4. Use isNaN: Ensure that isNaN() is used to check for NaN values.
## Code Style
1. Valid typeof Checks: Ensure typeof checks are valid.
2. Accessor Pairs: Ensure that whenever a getter is defined, there should also be a corresponding setter.
3. Block-Scoped Variables: Enforce the use of block-scoped variables.
4. Camelcase: Enforce camelCase naming convention.
5. Capitalized Comments: Ensure that comments are capitalized.
6. Class Methods Use this: Ensure that class methods utilize this, preventing unnecessary static methods.
7. Curly Braces: Always use curly braces in control structures (e.g., if, else, for, while).
8. Default Case Last in Switch: Ensure that the default case is always last in switch statements.
9. Default Parameters Last: Ensure that default parameters are placed last in function signatures.
10. Dot Notation: Enforce the use of dot notation whenever possible.
11. Strict Equality (===): Enforce the use of strict equality (===) and inequality (!==).
12. Grouped Accessor Pairs: Ensure getter and setter pairs are grouped together in the code.
13. ID Length: Enforce minimum and maximum length for identifiers, with exceptions for common short names like i, j, etc.
14. Max Nested Callbacks: Limit the depth of nested callbacks to 3 levels.
15. New Cap: Ensure that constructor functions are called with new.
16. No Case Declarations in Switch: Disallow lexical declarations in case/default clauses.
17. No Empty Statements: Disallow empty statements, such as unnecessary semicolons.
18. No Empty Functions: Prevent defining empty functions.
19. No Empty Static Blocks: Avoid creating empty static blocks in classes.
20. No null Comparisons: Avoid using == or != to compare against null.
21. No eval: Disallow the use of eval() to prevent security risks.
22. No Extending Native Objects: Prevent extending or modifying native objects.
23. No Extra Labels: Disallow unnecessary labels in code.
24. No Global Assignments: Disallow assignments to global variables or read-only properties.
25. No Inline Comments: Prevent the use of inline comments after code on the same line.
26. No Lone Blocks: Disallow unnecessary nested blocks.
27. No Lonely if Statements: Disallow if statements as the only statement in an else block.
28. No Function in Loop: Disallow functions declared inside loops.
29. No Multi-Assignment: Prevent multiple variable assignments in a single statement.
30. No Nested Ternary: Disallow nested ternary expressions for better readability.
31. No New Function: Prevent the use of new Function() to create functions.
32. No Object Constructor: Avoid using the Object constructor.
33. No Parameter Reassignment: Disallow reassignment of function parameters.
34. No Variable Redeclaration: Prevent redeclaring variables.
35. No Assignment in Return: Disallow assignments within return statements.
36. No Shadowing: Prevent variable shadowing to avoid confusion.
37. No Shadowing of Restricted Names: Disallow shadowing of restricted names, such as undefined.
38. No Undefined Initialization: Disallow initializing variables to undefined.
39. No Unnecessary Ternary: Disallow unnecessary ternary expressions.
40. No Unused Labels: Prevent defining labels that are never used.
41. No Useless Call: Disallow unnecessary calls to functions.
42. No Useless Catch: Prevent unnecessary catch clauses.
43. No Useless Computed Keys: Avoid unnecessary use of computed keys in object literals.
44. No Useless Constructor: Prevent defining constructors that do nothing.
45. No Useless Escape: Disallow unnecessary escape characters in strings and regular expressions.
46. No Useless Return: Avoid unnecessary return statements.
47. No var Declaration: Disallow the use of var and encourage





