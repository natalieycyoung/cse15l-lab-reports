# Lab Report 5 Week 10 - `diff`

First published: 2022-03-11  
Last modified: 2022-03-11

[Lab 9: Bash Scripts](https://ucsd-cse15l-w22.github.io/week/week9/)

[Lab 10: CommonMark Parser](https://ucsd-cse15l-w22.github.io/week/week10/)

[Report Guidelines](https://ucsd-cse15l-w22.github.io/week/week10/#lab-report-5)

Links:
- [My markdown-parse repo](https://github.com/natalieycyoung/markdown-parse)
- [The CSE15L markdown-parse repo](https://github.com/ucsd-cse15l-w22/markdown-parse)

In this lab report, I will discuss the results of two tests from commonmark-spec on my implementation and the course implementation of `markdown-parse`. I used a bash script to loop through the directory containing the test files and run my implementation of `MarkdownParse.java` with each file. After outputting the results to text files and using `diff`, I found that the two tests had different results.

## Test 1

The test:  
![9-test-1](Images/9-test-1.png)

The `.md` file:  
![9-file-1](Images/9-file-1.png)

	[foo](/bar\* "ti\*tle")

### Discussion

I think 

## Test 2

The test:  
![9-test-2](Images/9-test-2.png)

The `.md` file:  
![9-file-2](Images/9-file-2.png)

	[link](\(foo\))	

### Discussion

