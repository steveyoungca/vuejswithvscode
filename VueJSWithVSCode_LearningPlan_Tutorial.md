# VueJSwithVSCode
This is the code used in the VueJS Learning Plan
# Learning Paths: Setting up VueJS with VSCode

#### <i>Steve Young CSA Data & AI - Microsoft</i>

<p style="border-bottom: 1px solid lightgrey;"></p>

<h2><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/bookmark-3x.png?raw=true">How to Get Started with VueJS with VSCode</h2>  

This all started with me wanting to have a test harness to use various Microsoft Azure Cognative Services samples in a web based UI. I needed the ability to do some rapid prototyping while being able to house a couple of different projects and demonstrations for workshops. This tempate is the solution I came up with, while leverageing an amazing community.

Vuejs is a JavaScript library for building web based applications user interfaces and has built-in suport in VSCode.  There is a reference below to [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) which provides Vue tooling for VS Code.  This provides syntax-highlighting,snippets,Linting / Error Checking and Formatting for VueJS in VSCode.

A great resource in using and setting up VSCode with VueJS from the Visual Studio team - [Using Vue in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/vuejs-tutorial).  

A great tutorial from Code Maze, [Creating Vue.js Client Side – Preparing Project and Project Structure Overview](https://code-maze.com/creating-vuejs-project/)  which not only goes through steps for this process, but the group also provides a good set tutorials in various technologies.

This learning plan is expanded with the additional tools and items I used to create my quick and easy test bed.

<h3><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/bookmark-3x.png?raw=true"> Level 000 - The Prerequisites</h3> 

<h4><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/key-2x.png?raw=true"> Objectives</h4> 

- Review the basic knowledge required for this Learning Plan

This tutorial assumes you have basic Javascript and NPM knowledge.  The tutorial details the resources required to get up and running in a Windows environment, but the steps are similar in other envieonments.

I wrote a how to article; [How to Setup VSCode for Python and GitHub Integration](https://5minutebi.com/2019/03/14/how-to-setup-vscode-for-python-and-github-integration/) on my website, [5MinuteBI.com](https://5minutebi.com/) which goes into detail on installing VSCode and Git integraition which can help out with some of the setup.

<h3><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/bookmark-3x.png?raw=true">Level 100: Setting up & VSCode Extensions</h3>


<h4><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/key-2x.png?raw=true"> Objectives</h4> 

- Know what is required to set up the basic envrionment

Once you have installed VSCode, [details here](https://code.visualstudio.com/), there are some basic items that you need to have.

**NPM and NodeJS**
[Install NPM and Node.js](https://www.npmjs.com/get-npm) - This link provides details on NPM and information on various packages. 
[NPM Documentation & Tutorials](https://docs.npmjs.com/) - Should be the first step in learning NPM!!

**GitHub**
It goes without saying that you need a code repository. I use [GitHub.com](https://github.com) which has a free and paid level. The following links provide some information on setting up and using GIT.

[Installing GIT](https://git-scm.com/downloads) - the Git software release. When you install GIT you will have the option to select your default 

[GIT Documentation and Tutorials](https://git-scm.com/doc) - Reerence manual and free books to get your started.  Link also includes videos

[Git Commandline Cheatsheet](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf) - Various commands provided by the GIT project.

[GitHub.com](https://github.com) - A Development platform to host, manage projects and helps build software projects.

[GitHub Desktop](https://desktop.github.com/) - Rather then the command line, you can use the GITHUB desktop rather than the GIT Command line.  I use this to do Pulls from my Github repository and do all of my commits from VSCode.  Once you do a pull from GitHub Desktop, you get the option to open VSCode in this Folder, if you setup VSCode as the default code IDE when you install Git. 

**VSCode Extensions**
There are a number of extensions for VSCode that I always install in a new system.

[VSCode Installing Extensions Gallery](https://code.visualstudio.com/docs/editor/extension-gallery) - This link provides documentation on installing extensions and also a gallery of what extensions are available. VS Code extensions let you add languages, debuggers, and tools to your installation to support your development workflow.

[GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) - allows you to review and manage GitHub pull requests in Visual Studio Code.  Good integration, Authenticating and connecting VS Code to GitHub.

[VSCode Markdown preview](https://code.visualstudio.com/Docs/languages/markdown#_markdown-preview) - VS Code supports Markdown files out of the box. You just start writing Markdown text, save the file with the .md extension and then you can toggle the visualization of the editor between the code and the preview of the Markdown file; obviously, you can also open an existing Markdown file and start working with it. To switch between views, press Ctrl+Shift+V in the editor. You can view the preview side-by-side (Ctrl+K V) 

[Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles) - Changes VS Code's built-in markdown preview to match Github's styling.  This extensions allows side by side viewing and I find has a better view IMHO.  

[NPM Extension](https://marketplace.visualstudio.com/items?itemName=eg2.vscode-npm-script) - This extension supports running npm scripts defined in the package.json file and validating the installed modules against the dependencies defined in the package.json.

[mssql for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql) - Welcome to mssql for Visual Studio Code! An extension for developing Microsoft SQL Server, Azure SQL Database and SQL Data Warehouse everywhere with a rich set of functionalities, including Connecting to Microsoft SQL Server, Azure SQL Database and SQL Data Warehouses.

[Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur) - Vue tooling for VS Code, [Documentation](https://vuejs.github.io/vetur).  This has syntax-highlighting,snippets,Linting / Error Checking and Formatting.

[vscode-pdf](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf) - Allows the display of PDF files in VSCode.

<h3><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/bookmark-3x.png?raw=true">Level 200: Beginning VueJS - the CLI</h3>


<h4><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/key-2x.png?raw=true"> Objectives</h4> 

- Setup the Template for Coding in your VSCode project.

In this section the following resources will help to setup your project and get ready to code.

My first step is usually setting up my GitHub repository.  I do this through the [GitHub Website](https://github.com/), create an empty readme.md, and a .gitignore file based on **Node**, then do a pull in GitHub Desktop.  This provides a VScode folder.

[Vue Command Line Interface (CLI)](https://cli.vuejs.org/) provides the framework plumping or tooling and starter code and setup.  Installing through NPM si as shown in the lined article.

<img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/key-2x.png?raw=true">


===========================================================================================

<h3><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/LearningPlans/blob/master/media/bookmark-3x.png?raw=true"> More Resources & References</h3>

[Using Vue in Visual Studio Code](https://code.visualstudio.com/docs/nodejs/vuejs-tutorial)

[Getting VSCode for your platform](https://code.visualstudio.com/)

Tutorial - [Getting Started with VSCode](https://code.visualstudio.com/docs)

Video - [Various Introductory Video to get up and running quickly](https://code.visualstudio.com/docs/getstarted/introvideos)


<h3><img style="float: left; margin: 0px 15px 15px 0px;" src="https://github.com/steveyoungca/VueJSwithVSCode/blob/master/media/screengrabs/CLIInstall.png?raw=true"> End Notes</h3>

<sup>1</sup> Learning styles - Wikipedia.org – [https://en.wikipedia.org/wiki/Learning\_styles Sept 28,2019](https://en.wikipedia.org/wiki/Learning_styles%20Sept%2028,2019)