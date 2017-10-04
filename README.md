# Ansible Role - common

Common tasks for all ansible projects

Available on Ansible Galaxy: [pgkehle.common](https://galaxy.ansible.com/pgkehle.common)

# Examples

```YAML
- hosts: all
  roles:
    - { role: pgkehle.common, tags: ['always'] } # Use the `always` tag for when other tags get used
```
## License

MIT

## Author Information

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))

## For local development testing

```bash
rsync -av --delete ~/code/ansible-common/* ~/.ansible/roles/pgkehle.common
```
