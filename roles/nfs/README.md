```yml
- hosts: nfs
  roles:
    - role: nfs
      vars:
        nfs_exports:
          - path: /data, 
            ip: 172.16.1.0/24 
```
