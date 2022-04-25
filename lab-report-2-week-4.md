# LAB 2 Blog 
## Step by step tutorial on creating test files!
**Part 1: Code Change** <br><br>
Code Change Failure<br>
![Image](https://i.ibb.co/373Pcx6/Screen-Shot-2022-04-24-at-11-33-13-PM.png)<br><br>
**Part 2: Test File Explanations** <br><br>
Test 1: No brackets around the actual link url.<br>
[Link](https://raw.githubusercontent.com/mchouthai/markdown-parser/main/test-one.md)<br>
Reason for bug: The url link needs () brackets around it so that it is recognized as a link in markdown language.<br><br>
Test 2: Add a new line to the end of the md file using <br>.<br>
[Link](https://raw.githubusercontent.com/mchouthai/markdown-parser/main/test-two.md)<br>
Reason for bug: Adding a new line breaks the code as there is no bracket nor link and the code is designed to find (,),[,] and then print out an output so when it finds nothing it gets confused. <br><br>
Test 3: Replace [] with ().<br>
[Link](https://raw.githubusercontent.com/mchouthai/markdown-parser/main/test-three.md)<br>
Reason for bug: There is no [, and [ is needed to start the indexing for indexOf. As such the code cannot spot any links cause it needs [ to begin looking.<br><br>
**Part 3: Symptoms** <br><br>
Showing test-file.md passing without error and error messages for test-one.md, test-two.md, and test-three.md. 
![Image](https://i.ibb.co/9Wdwz6Y/Screen-Shot-2022-04-24-at-11-44-01-PM.png)






