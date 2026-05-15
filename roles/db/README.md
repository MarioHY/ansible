- hosts: dbs
  vars:
    # 这里覆盖 Role 里的默认变量
    db_root_password: "mariohy"
    service_user: "mariohy"
    service_password: "mariohy"
  roles:
    - db
