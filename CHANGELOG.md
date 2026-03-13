# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-03-09

### Added

- Initial release
- K3s cluster deployment on Proxmox (control plane + workers)
- EC2-like instance types (t3.small - t3.2xlarge)
- Cloud-init based K3s installation and configuration
- Configurable K3s version, CNI, and disabled components
- Static IP and network configuration
- SSH key authentication
- Tag support
