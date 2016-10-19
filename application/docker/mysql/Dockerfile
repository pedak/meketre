FROM mysql/mysql-server:8.0

ENV MYSQL_ROOT_PASSWORD test1234
ENV MYSQL_USER litwebdb
ENV MYSQL_PASSWORD litwebdb
ENV MYSQL_DATABASE litwebdb
ADD dump.sql /docker-entrypoint-initdb.d/00-import-data.sql
#RUN /entrypoint.sh mysqld & sleep 30 && killall mysqld
                                                                                                                                                                      
                                                                     

