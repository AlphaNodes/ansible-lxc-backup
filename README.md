# Ansible Role: LXC-Backup

Run LXC instance backups on Debian and Ubuntu servers.

## Dependencies

Installed LXC

## Example Playbook

    - hosts: server-name
      vars:
        lxc_backup_sets:
          - name: instance1
            with_stop: yes
          - name: instance2
            with_stop: no
      roles:
        - AlphaNodes.lxc-backup

## License

GPL Version 3

## Author Information

This role was created in 2018 by [AlphaNodes](https://alphanodes.com/).
