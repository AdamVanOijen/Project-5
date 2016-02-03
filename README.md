http://52.33.138.139/
port:2200

summary of software installed and config changes made:
  software installed:
    postgresql
    sqlalchemy
    flask 
    oauth2
    
  config changes made:
    configured ssh daemon to port 2200
    disabled root ssh login
    enabled firewall
    set firewall open ports to 80, 123, 2200
    configured web server:
      enabled mod_wsgi
      configured wsgi user
    configured postgresql:
      added postgreSQL user catalog
      added databse catalog
      granted all permissions for catalog to catalog
      disabled ssh password authentication; enforced RSA encryption
    
    
