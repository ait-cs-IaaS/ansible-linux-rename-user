# Ansible Role: linux_rename_user

This role can be used to rename a user and move their home directory.

## Role Variables

- `rename_user_src`: The user to rename
- `rename_user_target` The target username


##Example Playbook

```yaml
    - hosts: servers
      roles:
         - role: linux_rename_user
           rename_user_src: john
           rename_user_target: jane
```

## License

GPL3

## Author Information

Benjamin Akhras
Maximilian Frank
