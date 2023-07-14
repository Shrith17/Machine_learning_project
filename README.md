# Machine_learning_project
This is my first machine learning project.



software and account Requirement.
 1. [Github](https://github.com)
 2. [Heroku](https://signup.heroku.com/)
 3. [GIT cli](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)
 4. [Pycharm IDE](https://www.jetbrains.com/pycharm/download/?section=mac)

creating conda environment 
'''

conda create -p venv python==3.7 -y
'''

'''
conda activate venv/
'''


pip install -r requirements.txt
''''

to Add files to git
'''
git add .
''''

or
''''

git add <file_name>
''''

> NOTE: to ignore file or folder from git we can write name of file and folder in .gitignore file

to check git status
'''
git status
''''

to check all version maintained by git
''''

git log
''''

to create version/commit all changes by git
''''
git commit -m "message"
''''

to send version or changes to github

''''
git push origin main
''''

to check remote url
''''
git remote -v
''''






BUILD DOCKER IMAGE
''''
docker build -t <image_name>:<tagname> .
''''

> NOTE: image name for docker must be lowercase
> 