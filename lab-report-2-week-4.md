# Lab Report 2 Week 4

[Lab 3: Incremental Programming and Debugging](https://ucsd-cse15l-w22.github.io/week/week3/)

[Lab 4: When Tests Accumulate](https://ucsd-cse15l-w22.github.io/week/week4/)

[Report Guidelines](https://ucsd-cse15l-w22.github.io/week/week4/#week-4-lab-report)

## 1. [Code Change 1](https://github.com/natalieycyoung/markdown-parse/commit/e98aaff90a2c625a3085ec1f47441dc2638ea95d)
In lab 3, we came across a bug where the program wouldn't be able to skip lines and included links that were not in proper format.

Code changes:
![code-change-1](Images/3-code-change-1.png)

[test-file1.md](https://github.com/natalieycyoung/markdown-parse/blob/main/test-file1.md) was used as the input:
![test-file1](Images/3-created-test-file1.png)

**Relationship between bug, symptom, and input**
`test-file1.md` is the _failure-inducing input_ to `MarkdownParse.java`: due to a _bug_ in the body of the `while` loop (`toReturn.add(markdown.substring(openParen + 1, closeParen))`), it caused a _symptom_ in which the program printed the first line of the test file's contents despite it not containing a link.

## 2. Code Change 2
In lab 3, we came across a bug where the program wouldn't be able to skip lines and included links that were not in proper format.

Code changes:
![code-change-2](Images/3-code-change-2.png)

[test-file2.md](https://github.com/natalieycyoung/markdown-parse/blob/main/test-file2.md) was used as the input:
![test-file2](Images/3-created-test-file2.png)

**Relationship between bug, symptom, and input**

`test-file2.md` is the _failure-inducing input_ to `MarkdownParse.java`: due to a _bug_ in the body of the `while` loop (`toReturn.add(markdown.substring(openParen + 1, closeParen))`), it caused a _symptom_ in which the program printed the first line of the test file's contents despite it not containing a link.

![vscode](Images/vscode.png)

## 2. Bug Fix 2


![vscode](Images/vscode.png)
