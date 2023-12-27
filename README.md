Initialize the source code as git repo

`git init .`

Connect local source code to github repo
`git remote add origin https://github.com/MANSI181993/html_demo.git`

Adding changes and commiting:
`git add <file name>` or `git add .`
Now we are ready to commit the changes:
`git commit -m "This is my initial change"`

Now we are ready to push our changes to remote (remote is github.com)
`git push origin main` 

but when you start working on new branches:
`git push origin <branch-name>`