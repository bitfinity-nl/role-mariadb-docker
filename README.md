# role-mariadb-docker
This role contains the setup of a MariaDB server with docker.

# Access to MariaDB
- Access docker: ``docker exec -it mariadb bash``
- Access database: ``docker exec -it mariadb bash -c 'mariadb -u root -p'``

# Source(s)
- https://hub.docker.com/_/mariadb
- https://hub.docker.com/r/phpmyadmin/phpmyadmin/
- https://migueldoctor.medium.com/run-mariadb-phpmyadmin-locally-in-3-steps-using-docker-6b5912ff37c9
- https://techoverflow.net/2020/12/01/how-to-backup-data-from-docker-compose-mariadb-container-using-mysqldump/
  
