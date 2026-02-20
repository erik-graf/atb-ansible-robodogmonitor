# Ansible-Role: atb-ansible-robodogmonitor

Installs the robodogmonitor via ansible.

## Requirements

- Debian or Ubuntu

## Role Variables

```yaml
robodogmonitor_status: "OK"
robodogmonitor_wrapper_path: "/usr/local/bin"
robodogmonitor_wrapper_mode: "0755"
```

## Example Playbook

```yaml
- hosts: localhost
  roles:
    vars:
        robodogmonitor_wrapper_path: "/media/health"
        robodogmonitor_wrapper_mode: "0777"
        robodogmonitor_server: 192.168.100.23
```

## License

GPL-3.0

## Author

- Erik Grafendorfer
