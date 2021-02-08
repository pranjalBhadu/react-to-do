# Learning React

This reposidtory is to track my progress while learning React.

Using the mozilla developer notes

# Basic git commands

1. git init: to initialise git to our repo
2. git remote add origin <github repo link>: initilizes a github repository
3. git status: to know the currently changed and added files to git
4. git add .: adds all the files to the staged area of git
5. git commit -m "message": Commits all the changes in the staged area with given message
6. git branch -M main
7. git push -u origin main
  
# Basic structure of react files
  
making a react folder:

```
npx create-react-app moz-todo-react
```

src: working files are present here
public: contains the files read by the browser while we develop the app
package.json: contains all the information used by npm to keep the project organised

app.js file

import statements: allows us to use the code that is defined somewhere else in the project
(React module is not a file but it is listed as a dependency in the package.json file)

app-component: uses pascal case variable names

export statements: allow the app  component to be used  by other files
