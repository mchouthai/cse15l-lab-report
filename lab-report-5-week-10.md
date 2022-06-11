# Blog 5
## Testing Markdown Parser 

[My markdown-parser repository](https://github.com/mchouthai/markdown-parser.git) <br>
[Reviewed markdown-parser repository](https://github.com/nidhidhamnani/markdown-parser.git) <br><br>
*Using vimdiff to check difference in outcomes for the test files*<br>
*Testing on test file 363 and 367*<br><br>
**Difference between my markdown-parser file and cse 15l markdown-parser file using vimdiff**<br>
![Image](https://i.ibb.co/DC78RWM/Screen-Shot-2022-06-10-at-8-33-05-PM.png)<br><br>
[Test file 363 md file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/363.md)<br>
[Test file 363 html test file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/363.html.test)<br><br>
[Test file 367 md file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/367.md)<br>
[Test file 367 html test file](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/367.html.test)<br><br>
**Test File outcomes**<br><br>
I think neither of the outcomes (my markdown-parser and cse15l markdown-parser) are correct. <br><br>
*Using CommonMark demo site to check the actual outcomes for test file 363 and 367.*<br><br>
![Image](https://i.ibb.co/b3dd7F8/Screen-Shot-2022-06-10-at-9-20-23-PM.png)<br><br>
**Discussion about results**<br><br>
**Test 363**
My markdown parser did not work, because the markdown file had no brackets and my MarkdowParse.java expects brackets to be present in order to get the Link. The cse markdown parser printed out bar because bar was surrounded by parenthesis and thats the expectation to return a link for the getLinks function. <br><br>
*My markdown parse code*<br>
![Image](https://i.ibb.co/kJWy5Y6/Screen-Shot-2022-06-10-at-9-24-06-PM.png)<br><br>
*Cse 15l markdown parse code*<br>
![Image](https://i.ibb.co/0JvmP8Z/Screen-Shot-2022-06-10-at-9-23-48-PM.png)<br><br>
**Test 367**
My markdown parser did not work, because the markdown file had no brackets and my MarkdowParse.java expects brackets to be present in order to get the Link. The cse markdown parser printed out * foo because it was surrounded by parenthesis and thats the expectation to return a link for the getLinks function. <br><br>
*My markdown parse code*<br>
![Image](https://i.ibb.co/kJWy5Y6/Screen-Shot-2022-06-10-at-9-24-06-PM.png)<br><br>
*Cse 15l markdown parse code*<br>
![Image](https://i.ibb.co/0JvmP8Z/Screen-Shot-2022-06-10-at-9-23-48-PM.png)<br><br>




