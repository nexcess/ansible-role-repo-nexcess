# Ansible Role: Nexcess SCL Yum Repo

Installs Necxess' repo for RHEL/CentOS.

## Requirements

This role only is needed/runs on RHEL and its derivatives.

## Role Variables

See `defaults/main.yml`.

## Dependencies

None.

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-repo-nexcess.git
      name: nexcess.repo

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.repo

## License

MIT / BSD
