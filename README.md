#summary of software installed and config changes made:
##software installed
* postgresql
* sqlalchemy
* flask 
* oauth2

##config changes made
* configured ssh daemon to port 2200
* disabled root ssh login
* enabled firewall
* set firewall open ports to 80, 123, 2200

##configured web server
* enabled mod_wsgi
* configured wsgi user
* configured postgresql:
* added postgreSQL user catalog
* added databse catalog
* granted all permissions for catalog to catalog
* disabled ssh password authentication; enforced RSA encryption
    
ip:   52.33.138.139
port: 2200
user: grader

to gain access to the server run ssh -i ~/.ssh/grader_key.rsa grader@52.33.138.139 -p 2200

url to web application:  http://52.33.138.139/

###NOTE TO THE REVIEWER
Im sorry but when I submitted this project I forgot to put the rsa code in the 'notes to the review' section. I sent an email to the support team telling them to send you the rsa key, but if you have not recieved the rsa key from the support team, please contact them for it.
