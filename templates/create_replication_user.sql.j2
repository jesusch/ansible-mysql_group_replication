SET SQL_LOG_BIN=0;
CREATE USER '{{ mysql_gr_replication_user }}'@'%';
GRANT REPLICATION SLAVE ON *.* TO '{{ mysql_gr_replication_user }}'@'%' IDENTIFIED BY '{{ mysql_gr_replication_user_pass }}';
FLUSH PRIVILEGES;
SET SQL_LOG_BIN=1;
CHANGE MASTER TO MASTER_USER='{{ mysql_gr_replication_user }}', MASTER_PASSWORD='{{ mysql_gr_replication_user_pass }}' FOR CHANNEL 'group_replication_recovery';
