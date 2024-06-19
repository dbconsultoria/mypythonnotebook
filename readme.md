Original video link https://www.codehamster.com/codes/python/install-jupyterlab-with-docker-compose/

* make a directory
* download the “docker-compose.yml” file into this directory
* run “docker-compose up” in terminal
* go to the jupyterlab: “http://192.168.99.102:10000”
    * http://localhost:10000/tree
* If it is your first exec:
    * get the token shown in terminal
    * set the password by adding the token and new pswd in the opening page
* login success!

* After the container is created
    * docker-compose start
    * docker-compose stop