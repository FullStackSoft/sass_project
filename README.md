# SASS & SCSS exercise translator to CSS
## This is a document with a sass and scss exercise and hot to translate to css file. Here are the following steps.

1. Create a Project Folder and Position inside the project directory
2. Create a local git repository
```
    $ .git init
```
3. Create a git ignore file to ignore files to not upload into remote repository.
```
    $ .gitignore
```
4. Initiate npm package inside the directory so it can create a package.json file. Answer all the prompted default questions and accept with Yes at the end.
```
    $ npm init
```
5. Install the npm desired dependency in this case scss so it will update on the json file.
```
    $ npm install scss
    or 
    $ npm install sass

    also this will work

    $ npm install sass --save-dev 
```
6. in the current directory open two directories. First directory will be create and store the .sass or .scss files with the appropiate format. Second directory will be converted or translate the .scss and/or .sass files into the CSS files using the same name created initially only will be converted into css format.
   
7. open package.json file to add the converting syntax like the example below.
```
    "scripts": {
    "translatorName": "extensionFile ./inputFolder/:./outputFolder/",

    real example:

    "scripts": {
    "translate": "sass ./sass_scss_input/:./css/",
    
  },
```
8. in terminal enter the command to start the translation
```
    $ npm run 'translatorName'

    ex:

    $ npm run translate
```
this will create the new files with .css into the output directory.

9. At this point you should have a translated files into the output folder with extension .css

10. create an index.html file inside the project directory and link the .css and translated .css file.
    
11. BONUS::::
    Add this directory folder into a remote repository.

12. Create a repository name in github and copy the HTPPS or SSH address to add it in your project directory.

13. position the terminal inside the project directory and copy the following commands
```
    git init
    git add .
    git commit -a -m 'Initial commit'
    git remote add origin git@github.com:username/repo.git 
    
```

14. in case you need to change from master to main use the next command
```
    $ git branch -m master main
````

15. now you can push it with the following command 
```
    $ git push -u origin
```







