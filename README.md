# Ansible Role: ant

Installs ant on RHEL/CentOS.

## Requirements

- ansible >= 2.3

## Role Variables
Refer to `defaults/main.yml` in detail.
```
ant_download_folder: /opt
ant_download_url: https://www.apache.org/dist/ant/binaries/apache-ant-1.10.1-bin.tar.gz
ant_name: "{{ant_download_folder}}/apache-ant-1.10.1"
ant_archive: "{{ant_download_folder}}/apache-ant-1.10.1-bin.tar.gz"
```

## Dependencies

None.

## Example Playbook
```
- hosts: host
  roles:
    - role: ansible-role-ant
```

## License

None.

## Author Information

This role was created by Shinya Sasaki.
