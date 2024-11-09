# Ansible Role: Swag

[![GitHub last commit](https://img.shields.io/github/last-commit/ursinn-ansible/role-swag?logo=github&style=for-the-badge)](https://github.com/ursinn-ansible/role-swag/commits)
[![License](https://img.shields.io/github/license/ursinn-ansible/role-swag?style=for-the-badge)](https://github.com/ursinn-ansible/role-swag/blob/main/LICENSE)

Docker Image: https://docs.linuxserver.io/general/swag

## Options

| Option | Default Value |
| ---- | ---- |
| role_swag_image: | lscr.io/linuxserver/swag |
| role_swag_container | swag |
| role_swag_puid | 1000 |
| role_swag_pgid | 1000 |
| role_swag_tz | Europe/Zurich |
| role_swag_dir | /opt/docker-swag |
| role_swag_network | app-network |
| role_swag_htpasswd | |
| role_swag_force | no |
| role_swag_url | |
| role_swag_subdomains | wildcard |
| role_swag_validation | dns |
| role_swag_dnsplugin | cloudflare |
| role_swag_email | |
| role_swag_only_subdomains | false |
| role_swag_extra_domains | |
| role_swag_dns_cloudflare_api_token | 0123456789abcdef0123456789abcdef01234567 |
| role_swag_proxy_confs | [promtail.subdomain] |

## License

This project is under the MIT License. See the [LICENSE](https://github.com/ursinn-ansible/role-swag/blob/main/LICENSE) file for the full license text.
