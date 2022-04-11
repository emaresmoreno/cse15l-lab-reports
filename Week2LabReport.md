<h1>Week 2 Lab Report</h1>
<h2>Installing VSCode</h2>
<p>In order to install VSCode I first download the appropriate program for my Windows computer by using the link below.
After downloading, I accepted any and all agrements. 
Then I click on the option <em><strong>create a desktop icon</strong></em> (which will help me effectively open VSCode on your desktop) and 
clicked <em><strong>Install</strong></em> and then <em><strong>Finish</strong></em>.(After youre done you will see the VSCode opening page, as seen in the screenshot below)
</p>

<https://code.visualstudio.com/download>

![Screenshot (138)](https://user-images.githubusercontent.com/103283819/162676067-02a95b0b-5af9-4350-838a-cfa54315b60a.png)

![Screenshot (117)](https://user-images.githubusercontent.com/103283819/162676216-dd614ba8-1430-4bb4-9162-4bc8585fdd9c.png)


<h2>Remotely Connecting</h2>
<p>In order to remotely connect I first whent to <em><strong>Settings</strong></em>, then clicked <em><strong>Apps</strong></em>, and while on <em><strong>Apps and Features</strong></em> I selected <em><strong>Optional Features</strong></em> 
and made sure to install <em><strong>OpenSSH Client</strong></em> and <em><strong>OpenSSH Server</strong></em>. After installing the OpenSSH programs and knowing my personalized CSE15L account(by using the link below), I opened a terminal and typed <em><strong>ssh cs15lsp22aeu@ieng6.ucsd.edu)</strong></em>. After it asked <em><strong>Are you sure you want to continue connecting(yes/no[fingerprint])?</strong></em>,
and I typed yes followed by my password.(The image below indicates how it will look like when all steps have been done correctly)
</p>

<https://sdacs.ucsd.edu/~icc/index.php>

![Screenshot (118)](https://user-images.githubusercontent.com/103283819/162676414-347dece5-60c5-47ad-aa93-6ec899efda22.png)


<h2>Trying Some Commands</h2>
<p>In the terminal you can do several commands that will identify different information about your code. Some commands include <em><strong> cd ~, cd, ls -lat, ls -a, ls -t</strong></em>
 and many more. Each command has its own result, for example,I wrote <em><strong>ls -lat</strong></em> in the terminal and it showed hidden files, modified files, and files in general. (return for this command is shown in the picture below)
</p>


![Screenshot (119)](https://user-images.githubusercontent.com/103283819/162676643-6745ce78-6f1a-4d02-9990-daba52a67555.png)

  
<h2>Moving Files with scp</h2>
<p> First I created a new file and added content to it. Then I wrote <em><strong>exit</strong></em> in my terminal followed by <em><string>scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/</strong></em> and my password.
Then I logged in using by typing <em><strong>ssh cs15lsp22aeu)@ieng6.ucsd.edu)</strong></em> and my passwrod, then typed in <em><strong>ls</strong></em>.(After you have successfully finished it will 
look like the picture below)
</p>


![Screenshot (120)](https://user-images.githubusercontent.com/103283819/162676745-fc97e5bc-2f48-480c-a76c-05b53c16ce92.png)

  
<h2>Setting an SSH Key</h2>
 <p> I began by typing <em><strong>ssh-keygen -t ed25519</strong></em> on the terminal and <em><strong>\Users\Evelyn/.ssh/id_ed25519</strong></em> when propted with <em><strong>Enter file in which to save the key</strong></em>. Then i cliked enter 
 each time it asked for a passprase.(After all steps have been completed it will look like the picture below)
 </p>
 
 
 ![Screenshot (139)](https://user-images.githubusercontent.com/103283819/162674941-0d4b81cf-1822-42dd-9cc0-38aeb087c5dd.png)
 
 
 <h2>Optimizing Remote Running</h2>
 <p> Learning the short cuts for VSCode I tried writting quotes on commands in order for them to run on the remote server and then exit. I also tried the semi clons in between the commands to run several commands at once.
  (example of one in the picture below)
  </p>
  
  
![Screenshot (141)](https://user-images.githubusercontent.com/103283819/162681414-74ed04bb-55fa-455d-bbf5-d1d567bcfbb3.png)



