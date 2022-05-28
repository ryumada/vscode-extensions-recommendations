# VSCode Workspace Extensions Recommendations
This repository contains the collections of my extensions lists while coding in Visual Studio Code (vs code). The lists are created based on the technology I used for development.

## The Repository Structure
The root folder started with the programming language I used. Inside of those folders contains the technologies/frameworks I used. Here is the structure of this repository in the tree view:

<pre>
.
└── programming-languages
    └── technology/framework
        └── <b>extensions.json</b>
</pre>

Example for [djangorestframework](https://www.django-rest-framework.org) workspace extensions recommendation:

<pre>
.
└── python
    └── djangorestframework
        └── <b>extensions.json</b>
</pre>


## How to add the list as your workspace recomendation?
You can place the file called `extensions.json` into your `.vscode` folder inside your project directory. Then, you can see the recommended extensions list by typing `@recommended` into the search bar on the extensions panel. See the screenshot below:

![](assets/vscode-workspace-recommended-extensions.png)  
