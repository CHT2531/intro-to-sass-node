# Intro to Sass with Node.js
If you aren't familiar with using command line tools, have a look at [Intro to the Command Prompt](intro-to-command-prompt.md) which explains the basics.

## Installing a Node.js version of Sass
* Open the Node.js Command Prompt (it must be the Command Prompt)
  * if you are doing this at home, you won't have a specialt Node.js Command Prompt and you can just use your regular Command Line interface e.g. Powershell. 
* Enter the following:

```
npm install -g sass
```

This installs the sass package. The *-g* flag specifies it should be installed globally so it will be available for all projects on the machine.

## Using node Sass
* Using the Command Prompt navigate to a web application folder where you have some Sass code
* In the Node.js command prompt, enter the following:
```
sass --watch sass/style.scss css/style.css
```
* This will look for a Sass file in a folder called *sass*, compile it and output it to a *css* folder. You might have to modify the above code for your file names, but if you've previously done the Koala Sass practical the naming should be the same.
* Make changes to your Sass file. You should get some feedback through the Command Prompt and *style.css* should update.
* Previously we used Koala. One limitation of Koala is that is doesn't use the most up to date version of Sass e.g. we had to use *@import* to combine multiple stylesheets. Have a look at the *@use* rule (https://sass-lang.com/documentation/at-rules/use) which is a better way of doing the same thing. Modify your Sass code to use *@use*.
* Once you've finished, in the Command Prompt enter *ctrl+c* to stop watching the Sass code.
