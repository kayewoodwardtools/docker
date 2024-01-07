# Sample nodejs application with docker Conatiner

github.com/codewithrajranjan/Nodejs-application-with-docker

# Installation


```javascript

    // clone the application with git clone

    // then install the npm modules using
     
    npm install


```


# Running the application


```javascript


    node server.js


```


# Building docker image

```bash

    docker build -t <imagename:version> .

```



# Running docker container


```bash

    // 9005 port is given since the docker file contains 9005 port
    docker run -it -d -p <outside-port-of-your-choice>:9005 <imagename:version>

```
git config --global user.email "kayewoodwardtools@outlook.com"

git config --global user.name "kayewoodwardtools"

npm install

git init

git branch -M main

git add .

git commit -m "first commit"

git remote add origin https://github.com/charlespan10/docs-.git

git push -u origin main

