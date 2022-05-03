<h1>Error: No end parenthesis </h1>

<https://github.com/emaresmoreno/markdown-parser/blob/main/testfile3.md>

![Screenshot (182)](https://user-images.githubusercontent.com/103283819/166411833-ae2a2674-65b6-4177-954a-038030f22909.png)



<p> The bug is that the code never stops running. The symptom is a StringIndexOutOFBoundsException error and the failure-inducing
 input is a link without closing parenthesis. All together it results with the code continuously running as it looks for the end parenthesis of the link; since 
 its not found by the time it reaches length 96 it returns an error saying that its out of bounds.
</p>

<https://github.com/emaresmoreno/markdown-parser/commit/96dc9577bff6241bc1591768e6b2a46cda18f29b>

![Screenshot (161)](https://user-images.githubusercontent.com/103283819/165000625-64fb1c64-d621-4a4f-85c9-24c136baa54f.png)


<h2>Solution </h2>
<p> In order to fix this error you must create an if statement that check wether or not there is an end parenthesis. To do so the boolean must check if the closeBracket 
 is equal to -1(which means its not found) and it is true add 1 to currentIndex. We know we have fixed the bug because it doesnt create an out of bounds error 
  and it does not return the incomplete link. 
</p>

<https://github.com/emaresmoreno/markdown-parser/commit/0fa0f13d9d2392dcd55b179710b79788afef1e60>


![Screenshot (165)](https://user-images.githubusercontent.com/103283819/165014214-b875b78e-18f2-47ba-8d25-d138a4736fe0.png)

<h1>Error: Images</h1>

<https://github.com/emaresmoreno/markdown-parser/blob/main/testfile2.md>

![Screenshot (180)](https://user-images.githubusercontent.com/103283819/166411577-871803a4-8839-4b21-a01b-b3c47efdf6bc.png)

<p> The bug is that it reads the image as a link. The symptom is that it returns the image as a link and the failure-inducing input is adding a image as an input. All 
 together the code reads the image link and incorrectly returns it as part of the link list. 
</p>


<https://github.com/emaresmoreno/markdown-parser/commit/37561f8ec3553f18ad35e38c74fefd15506da84c>

![Screenshot (167)](https://user-images.githubusercontent.com/103283819/165017507-0b1112cb-428a-40d1-a80b-b55bd5640697.png)

<h2>Solution </h2>

<p> You need to add a boolean that checks if there is an exclamation point in the beginning of the so called link which would indicate that it is not a link but rather
 an image. 
</p>

<https://github.com/emaresmoreno/markdown-parser/commit/e953d6cdf52e0ba63c6e2a65f83e3ffcd72996dc>

![Screenshot (169)](https://user-images.githubusercontent.com/103283819/165019665-56200d58-83d6-4823-92c8-f40d8eec75db.png)

<h1>Error:Just a comment </h1>

<https://github.com/emaresmoreno/markdown-parser/blob/main/testfile1.md>

![Screenshot (176)](https://user-images.githubusercontent.com/103283819/166410046-dbc84a6e-2533-4b62-8d3b-7a06c20d782c.png)


<p> The bug is that it goes through all the code in search of a starting and ending bracket and starting and ending parenthesis. The symptoms is a StringINdexOutOfBoundsException
 and the failure-inducing input is a comment or string without any ending and closing brackets and parenthesis. All together the codes goes through all the code and returns and error 
 indicating that they are not found and returns an error.
</p>

<https://github.com/emaresmoreno/cse15l-lab-reports/new/main>

![Screenshot (171)](https://user-images.githubusercontent.com/103283819/165020373-7c3e7650-0aea-4022-a0ef-b81fbf512a93.png)

<h2>Solution </h2>
<p> In order to fix it you need to make a boolean where you have to check if there is a starting, ending pathenthesis and brackets.
 </p>
 
 <https://github.com/emaresmoreno/markdown-parser/commit/2e1d1193062e1ddc9241887aadd773bc3969695a>

![Screenshot (173)](https://user-images.githubusercontent.com/103283819/165021151-ce0937f4-a0ca-4491-bd94-7f91add62a01.png)






