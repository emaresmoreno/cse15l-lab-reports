<h1>Week 6 Lab Report 3</h1>

<h2>Added Tests</h2>

<h3>My MarkdownParse</h3>

[My Repository](https://github.com/emaresmoreno/week5mdParse)

![image](https://user-images.githubusercontent.com/103283819/169711338-cacfba46-747a-4193-89dd-8c8dbbea0bff.png)

![image](https://user-images.githubusercontent.com/103283819/169723228-84be7b54-196a-4891-95d0-542bfad725d5.png)

<h3>Reviewed (Other Groups) MarkdownParse</h3>

[Reviewed Repository](https://github.com/emaresmoreno/OtherGroupsReview)

![image](https://user-images.githubusercontent.com/103283819/169711467-7d1ffac9-57d8-48ef-8051-a220b5015478.png)

![image](https://user-images.githubusercontent.com/103283819/169711555-97218d44-0341-402f-90bb-50b0475efc8f.png)

<h2>Comments</h2>
<h3>My MarkdownParse Possible Fixes</h3>

<p>Snippet1: For "snippet1" to work in my MarkdownParse it would be a small code change. I would make an if stament after line 29 checking if there is a "`"
 before the open bracket.</p>
 
```
 if(mardown.charAt(openBracket - 1) == '`'){
   currentIndex = closeParen + 1;
 }
```

<p>Snippet2: For "snippet2" to work in my MarkdownParse it would not be a small code change. 
  I would have to make my code check if there are multiple openBrackets and/or mutiple endParen, ect and to do so I would have to do 
  add another while statement or for loop that would go through verything in the file 
  and count how many of each (openParen, closeParen, openBracket, closeBracket) are in the file. Then going 
  into the already existing while statement I would have then add an if statement checking if there is more of each
  (openParen, closeParen, openBracket, closeBracket) and if so assign each their corresponding index number.</p>
 
 <p>Snippet3: For "snippet3" to work in my MarkdownParse it would be a small code change. For this snippet I would have to add to my code wether there is a space 
  to go on to the next character in the file in the form of an if statement. </p>
  
```
  if(mardown.charAt(currentIndex) == ' '){
    currentIndex += 1;
  }
```

<h3>Reviewed (Other Groups) MarkdownParse Possible Fixes</h3>

<p>Snippet1: For "snippet1" to work in the other groups MarkdownParse it would be a small code change. 
 I would make an if stament after line 29 checking if there is a "`"
 before the open bracket.</p>
 
```
 if(mardown.charAt(openBracket - 1) == '`'){
   currentIndex = closeParen + 1;
 }
```

<p>Snippet2: For "snippet2" to work in the other groups MarkdownParse it would not be a small code change. 
  I would have to make my code check if there are multiple openBrackets and/or mutiple endParen, ect and to do so I would have to do 
  add another while statement or for loop that would go through verything in the file 
  and count how many of each (openParen, closeParen, openBracket, closeBracket) are in the file. Then going 
  into the already existing while statement I would have then add an if statement checking if there is more of each
  (openParen, closeParen, openBracket, closeBracket) and if so assign each their corresponding index number.</p>
 
 <p>Snippet3: For "snippet3" to work in my MarkdownParse it would be a small code change. For this snippet I would have to add to my code wether there is a space 
  to go on to the next character in the file in the form of an if statement. </p>
  
 ```
  if(mardown.charAt(currentIndex) == ' '){
    currentIndex += 1;
  }
```
 <p>Overall both codes are extremely similar in what they do (not what they look like) and so in order to fix the errors it would
be by implimanting the same changes.</p>
 
 
