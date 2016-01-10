# linux_server_config

Below is the list of requirements for configuring a Linux Web Server for project 5 for Udacity.

i. **IP Address**  52.25.29.209 / **SSH Port** 2200

ii. **URL** http://ec2-52-25-29-209.us-west-2.compute.amazonaws.com

iii. **Applicatins that are installed/Configurations Made**
  1. Added a user 'Grader' to the server
  2. Gave the user sudo access
  3. Updated current package list and installed them.
  4. Updated the SSH port to 2200 and disabled root access.
  5. Added my local machine to the file /etc/hosts, to remove the warning that is returned when using sudo.
  6. Updated and enabled UFW to listen to the following ports (80, 2200, 123) (HTTP, SSH, NTP).
  7. Installed **Apache**.
  8. Installed **mod_wsgi**
  9. Installed **python-setuptools**
  10. Installed **git**
  11. Cloned the Item-Catalog application. https://github.com/cbones4321/Item-Catalog
  12. Installed the necessary dependencies for Apache to run a Flask application.
  13. Edit the default .conf file to point to the new ItemCatalog application.
  14. Installed **Postgres**
  15. Created a user Catalog with access to the Catalog Database used in the Item-Catalog application.
  16. Edit the file /etc/postgresql/9.3/main/pg_hba.conf to not allow remote connections.
  17. Updated oauth credentials to include the url above.

iv. Some resources that were helpful in setting up the server are: 
https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps
http://askubuntu.com/questions/59458/error-message-when-i-run-sudo-unable-to-resolve-host-none
