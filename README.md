Role Name
=========

Installs and configures a MySQL Group Replication cluster


Role Variables
--------------
```YAML
# name of the GR cluster. gets uuid encoded
mysql_gr_group_name: mycluster
# network interface where cluster communication will take place
mysql_gr_network_interface: eth0
# GR needs an additional listener where group communication is done
mysql_gr_network_port: 6606
# only use this during initial installation
mysql_gr_bootstrap: False
# GR replication user
mysql_gr_replication_user: 'repl'
# GR replication password
mysql_gr_replication_user_pass: 'repl'
```

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: mysql_group_replication
      roles:
         - ansible-mysql_group_replication

License
-------

BeerWare
