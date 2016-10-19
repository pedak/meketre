FROM nimmis/apache-php5
ADD http://downloads.sourceforge.net/project/refbase/refbase/refbase-0.9.6/refbase-0.9.6.tar.gz?r=https%3A%2F%2Fsourceforge.net%2Fprojects%2Frefbase%2Ffiles%2Frefbase%2Frefbase-0.9.6%2F&ts=1476805674&use_mirror=kent /tmp
RUN rm /var/www/html/*
RUN tar -xvzf /tmp/refbase-0.9.6.tar.gz -C /tmp && mv /tmp/refbase-0.9.6/* /var/www/html
ADD db.inc.php /var/www/html/initialize
