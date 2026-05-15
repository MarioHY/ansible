```yml
- hosts: dbs
  roles:
    - role: db_item  
      item_db_name: "wordpress"
      db_root_password: "mariohy"
      db_server_ip: "localhost"
```
