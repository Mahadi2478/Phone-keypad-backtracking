# Phone-keypad- Backtacking

Backtracking is like trying different paths, and when you hit a dead end, you give up the last choice and try a different route.
<br><br>
In a button phone, there are buttons named as 0 to 9. Every button indicates 3/4 english syllebles. If I write 23, where 2=abc and 3=def; I might get 9 different sylleble pair - ad, ae, af, bd, be, bf, cd, ce, cf. Backtacking algorithm helps us to give away the sylleble we don't want & see other options within the same number. <br>

<h3>Required data structures: Recursion, strings, list</h3>

Suppose I want 23= be <br>
So backtracking will help me to give up 2=a and follow the next match 2=b <br>
Then it will follow the next level b, gives up 3=d and follow the next match 3=e <br>


