# How to remove node_modules
1. Create a .gitignore file in the git repository if it does not contain one

##### touch .gitignore 

2. Open up the .gitignore and add the following line to the file

##### node_modules 

3. Remove the node_modules folder from the git repository

##### git rm -r --cached node_modules 

4. Commit the git repository without the node modules folder

##### git commit -m "Removed node_module folder" 

5. Push the repository to github

##### git push origin master

##### After all of that, you should also add the gitignore and commit it to the repository

##### git add .gitignore

##### git commit -m "Updated the .gitignore file

##### git push origin master