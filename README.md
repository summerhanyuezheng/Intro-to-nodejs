# Intro-to-nodejs
## Description
This is a program utilizing external npm(Node Package Manager) to generate random superhero & supervillain name on terminal.
## Techonology Installed
  - node.js (I installed from official website, but you can also use homebrew)
  - npm (coming with node.js)
## some of the steps/command I used:
  - `npm init`: this command initialize a project and create the package .json file, but make sure to run the command under the right directory. 
  - went to [npm external package page](https://www.npmjs.com/) find the package you want to utlize. In my case, [superheroes]    (https://www.npmjs.com/package/superheroes) and [supervillains](https://www.npmjs.com/package/supervillains) were used.
  - `npm install <packageName>` : this command adds the package you want to use as dependencies in package.json file. In my case, i used `npm install superheroes` and `npm install supervillains`
  - require the package in index.js in order to use it 
  - follow the package usage instruction and add code in index.js for it to work
  - `node index.js` : runs program and output one random superhero name and one random superbillain name each time.
 ## Screenshot 
 ![screenshot](https://github.com/summerhanyuezheng/Intro-to-nodejs/blob/main/Screen%20Shot%202023-04-25%20at%204.39.06%20PM.png)
 
  
 
 
 

