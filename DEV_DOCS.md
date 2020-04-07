## Developer Documentation

### Git

- I found the best way to work with on a project with two people is with a 3 branch system. A master branch and two working branches (one for each of us). This way we will never *disrupt* each others work. 
- I would create your own branch from master. See below on where to do this. Just enter text and press enter:
<img src="https://user-images.githubusercontent.com/26554691/70039098-550e7300-1587-11ea-964a-53a16a26729a.png" width="250" >

- Github Desktop Quick Explanation
    - You can change branches on local client (useful if you wanna check out what I'm working on). You should never be working in the Master branch. 
    
<img src="https://github.com/CrypticSquirrel/pics/blob/master/Screen%20Shot%202020-04-06%20at%209.53.17%20PM.png?raw=true" width="250">
    
    - After I make change(s) I commit it with some message. 
    
<img src="https://github.com/CrypticSquirrel/pics/blob/master/Screen%20Shot%202020-04-06%20at%209.53.10%20PM.png?raw=true" width="250"><img src="https://raw.githubusercontent.com/CrypticSquirrel/pics/master/Screen%20Shot%202020-04-06%20at%209.53.00%20PM.png?token=AGKTCQ775KFQXB5TWDKV2CS6SUMMA" width="250">
    
    - Push changes to remote (github.com)

<img src="https://github.com/CrypticSquirrel/pics/blob/master/Screen%20Shot%202020-04-06%20at%209.53.24%20PM.png?raw=true" width="250">

- Upload changes to the Master branch with a pull request. Click the button, enter a title, create pull request. We won't do code reviews (unless you want) so you can merge it right away (scroll down and find and click merge). 

<img src="https://user-images.githubusercontent.com/26554691/70040431-8f790f80-1589-11ea-8a0a-56bf5dd82335.png" width="250"> <img src="https://github.com/CrypticSquirrel/pics/blob/master/Screen%20Shot%202020-04-06%20at%2010.11.49%20PM.png?raw=true" width="400">

### (My) Development Environment 

**vscode**
- You can download vscode from their [website](https://code.visualstudio.com/) or using brew (command below)

```
brew cask install visual-studio-code
```

- If you use vscode I would highly recommend [this useful app](https://github.com/sozercan/OpenInCode). Lets you actually open projects (instead of just viewing files). Install w/ brew: `brew cask install open-in-code`

**useful vscode extensions**
- For this project I would recommend `live server` and `p5js Snippets`
- Download extensions by clicking the fourth tab down on the left (it looks like building blocks)

**live server**
- Live server lets you view the web page you are working on in real time. As soon as you make a change, it will update in the browser. After you've downloaded it you can access it by pressing "go live" or right clicking and selecting "open with live server" when you are on an HTML page. This will only work if you do it when you have a .html page open and active.

**github desktop**
- Although vscode has built in source control and git can be run on the command line, I prefer [github's desktop client](https://desktop.github.com/). because I can view all my projects in one place.

**brew**
- If you are on a mac, [brew](https://brew.sh/) is the best thing ever. Consider getting it. 
