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
Im sorry but when I submitted this project I forgot to put the rsa code in the 'notes to the review' section. 
Obviously under differenct circumstances, I would not publically put the rsa key to my server on the internet, so don't 
mark me down for doing it pls. 


Here is the key: 
-----BEGIN RSA PRIVATE KEY-----
MIIEpQIBAAKCAQEA0laP3skhNX8if6Yv3w5CkUyFQs/CmR1gdEiy/rvOP0T4qUYF
Qvg2FT6ysPzcreAAuFWvhrm/8BN9YNDsQKPJ+CyXks0072LIW6Xo+lr7AcH9LmU/
2kE7W3BMpiJyi/pJfX6jdmWYZUnajWUedYDh34a5dCF9wNQCs43fQVxWrS4IJH5Q
hVRUof7eFhTzgILycU12/pk/9Rkh0E+r7JtP9uHOq5UhUox3mzj0fpMNAyRkY22p
DCUp/WOj1VVkpND2wE0Qc3ttvQkqn+hwd4QyUnQEFSkPdEo1sf4+lgz1OmvrQtd/
UUgZ6Tf2aqcMTkqvhop/2bmjO52Bm7mzxK7JLQIDAQABAoIBAF+8IG2Rc/kKbaRV
+rH2ppvFjV30fCj+svkaYcYJqv0nIlrBUQHDQbJ3wBNIdBT7wLgl3+ddQhw+crGP
RgjBw9qeSTr7BZ3zgygboqfYoyiQp/DnCqIHUMH0oh53zVUizTI+Yp4v7aYkcEIt
BSkMSUJY6q4N1FPg633YFAaGxbi6SKPBKVqNGZq9ZGZeKYl7xmdMBwlBYtuq6EZp
ULd21WZGUOFB+xPO5Fw5yM5l+7qbiUqfCB98nv3bEb4f+p8/HMG0PB38z9b4hxqt
WyqCex7vz5f4VYUos7dgvY2Ut4r0b7VfkAFE3trL0o6HDKonXP0SfaDHKB8vbl6d
tmTeG60CgYEA6N3/sYGy5/PBdvPo22BUoc8qxucg/IAuA0/rItSbVKxe3KVHCNCL
tnUbHv6IH79NBGuhq1hVKAJAmK9oqP6ZjEWQKOxlaq06FwWtdYX5+YUhuxM9vp8h
wsSsNEUY+KnUHKT9R0SM85sBQyk4wtz49PbcL5QR6d7ixkOfTVmOZdcCgYEA5zuh
lZWyVIpFi9VQN77qYy3RCJBN5FbSjqbT2tVAQ4tK9BaJCSfutpDjGMZeEhG3+1tb
VYDCR9YhM6nNUMf5Bd8MHsCoBfbkNsm2SGZFKeZQQ4itqBnxXn30B+kSOIXzgLVk
Jk/JBqyYcMHeGnhh2FIdxhqmvx4z9b74I78d4JsCgYEA5jLfG4iNZULQE1lW7day
kyqKrQm60CGeWuPcHBh0XSXwuMoiCJKwKnRllSQlSM0Bw8bqkMnHlL91P/rWyYi2
HbZ+phXaw7Pu4udX6/+/d2ymRZrlxNTmuPVXDmzoHJk1+AMZ5iPb+s1WWCAd3nQ3
H2IRlG8ZrkoJf9lFV1+apw0CgYEAoSv/RLRCyIpYT08vyqtX1ClrOfzbTfz2ZlgB
8tYRJQNCC0Bp4+fhi38Ry4L4rr+K7biPwNkukcO/ALOqWFQKTv1ZBVZjx0R/bXDL
jUs7iijuaSQrZrAufR5tqdXazWsQfvXwCIQ0KmLDHlUC6pBeItmZxytsbmou7Wte
qgvcV2ECgYEAt/WIr7AA/qSibcFpRegZgFjm1Dh5Ndou8+ywPsVaTWcROQ7X0R0p
+ydXHVpMbebebAoY4o0ErJwzAEbBu2g0dbmrArT9PU/c/0SMsYKNR4WmYlVYhCo+
kfTsDRpq3qQfYLzSBC+qjdpt2pX2Bot5IcBnLywTAbpJ2BMu9V2rmjw=
-----END RSA PRIVATE KEY-----
