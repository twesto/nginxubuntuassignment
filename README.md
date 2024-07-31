Steps to pull, run and access the webpage from the assignment:
  1- pull the image from docker hub using: **docker pull twesto/nginxubuntu** 
  2- run the image using: **docker run -it -p 80:80 twesto/nginxubuntu**
  3- start nginx using: **service nginx start**
  4- make sure that nginx is running using: **service nginx status**
  5- open your local browser to check the webpage by using: **localhost:80/index.html**
