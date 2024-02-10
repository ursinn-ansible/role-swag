# Ansible Role: Swag

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-swag?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-swag/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-swag?style=for-the-badge)](https://github.com/ursinn-ansible/role-swag/blob/main/LICENSE)

Docker Image: https://docs.linuxserver.io/general/swag

## Options

| Option | Default Value |
| ---- | ---- |
| docker_swag_docker_image: | lscr.io/linuxserver/swag |
| docker_swag_docker_container | swag |
| docker_swag_docker_network | app-network |
| docker_swag_dns_cloudflare_api_token | 0123456789abcdef0123456789abcdef01234567 |
| docker_swag_puid | docker_files |
| docker_swag_pgid | docker_files |
| docker_swag_tz | Europe/Zurich |
| docker_swag_dir | /opt/docker-swag |
| docker_swag_htpasswd | |
| docker_swag_url | |
| docker_swag_subdomains | wildcard |
| docker_swag_validation | dns |
| docker_swag_dnsplugin | cloudflare |
| docker_swag_email | |
| docker_swag_only_subdomains | false |
| docker_swag_extra_domains | |
| docker_swag_force | no |
| docker_swag_proxy_confs | [promtail.subdomain] |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-swag/blob/main/LICENSE) file for the full license text.
