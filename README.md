# machine_learning_project2
## this is my first machine learning project.

1. [Github account](https://github.com)
2. [heroku account](https://dashboard.heroku.com/login)
3. [vs code ide](https://code.visualstdio.com/download)
4. [GIT Cli](https://git-scm.com/downloads)
5. [GIT Documentation](https://git-scm.com/docs/gittutorial)


Creating conda environment
```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```
or
```
conda activate venv
``` 
pip install -r requirements.txt
```

To add files to git
```
or
```
git add <file_name>
```

> Note: to ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
```
git status
```
to check all version maintain by git
```
git log
```

to create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```
to check remote url
```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information

HEROKU_EMAIL = vikashsingh5151@gmail.com
HEROKU_API_KEY = ddf52241-20e0-46e5-b9a4-09a59e48d383
HEROKU_APP_NAME = ml-regression-app-vikash 


BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase

To list docker images
```
docker images
```

run docker images
```
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
```

to check running container in docker
```
docker ps
```

Tos stop docker container
```
docker stop <container_id>
```