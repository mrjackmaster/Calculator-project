2021-04-06  Created repository for calculator project. Basic file setup.

2021-04-10  Basic operations and all buttons on keypad are working, decimals are fine too. Need to fix an issue with operator button not changing. Right now doing 5 + 5 + - 5 will result in 15 because second press on different operator button doesn't overwrite the previously assigned one, it's an easy fix, forgot to include it after rewriting code. Also pressing = multiple times doesn't add the previous number to current result. Some leftover code from attempting to create that function is leftover in the code. Also the code looks pretty bad because of rewriting it few times, large number of IF's, and all of that being tied to one EventListener. I'll finish this iteration of this messy code and rewrite it properly later on.

2021-04-13  Rewrote most of the code. Some bugs got reintroduced while doing so. Right now equals button doesn't add previous second value to the result, other operators keep assigning result from screen to second value and add it to result again. Also pressing different operator doesn't replace the currently chosen operator.