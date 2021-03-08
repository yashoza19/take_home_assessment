FROM mysql:5.7
# Add a database
ENV MYSQL_DATABASE employees
# Add the content of the sql-scripts/ directory to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
COPY ./sql-script/ /docker-entrypoint-initdb.d/
