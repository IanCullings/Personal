<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [If-Else Statements in Hydrogen](#if-else-statements-in-hydrogen)
- [Linter/Pycodestyle and Teletype](#linterpycodestyle-and-teletype)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# If-Else Statements in Hydrogen
If you are using Hydrogen and are using `Shift + Enter`, `Cmnd + Enter`, or `Cntrl + Enter` to run python code then you may have noticed an error when trying to use if-else statements similar to the one below.

![IfElseError](https://github.com/AguaClara/aguaclara_tutorial/wiki/Images/IfElse1.png)

I think this error comes from the fact that by running an if-else statement line-by-line the else is not properly associated with the if, leading to a syntax error. Fortunately the solution is simple, just highlight the entire block of code containing the if-else statement and then use `Shift + Enter`, `Cmnd + Enter`, or `Cntrl + Enter` to run it.

![IfElseSolution](https://github.com/AguaClara/aguaclara_tutorial/wiki/Images/IfElse2.png)

# Linter/Pycodestyle and Teletype
When editing Python code while using Teletype you may see an error similar to the one in the picture below. This error stems from something Teletype does when you are accessing a file that's not on your computer.

![LinterError](https://github.com/AguaClara/aguaclara_tutorial/wiki/Images/LinterError.png)

At the moment we don't have a fix, so just continue working as usual and try not to get too annoyed at all the red boxes popping up.
