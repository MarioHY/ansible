```bash
- hosts: redis
  roles:
    - role: redis
      vars:
        - redis_bind: 172.16.1.21

```
