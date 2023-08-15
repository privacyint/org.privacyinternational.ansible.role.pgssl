# pgSSL Ansible role

This is an [Ansible](https://www.ansible.com/) role which installs [pgSSL](https://github.com/glebarez/pgssl) to run as a [Docker](https://www.docker.com/) container wrapped in a systemd service.

This role *implicitly* depends on [`com.devture.ansible.role.systemd_docker_base`](https://github.com/devture/com.devture.ansible.role.systemd_docker_base).