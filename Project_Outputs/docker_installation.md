# Docker Installation

## Description

Installed Docker Engine and configured the Docker service on the Linux server.

### Commands Executed

* yum install docker -y
* systemctl start docker
* systemctl enable docker
* systemctl status docker

## Verification

Verified Docker service status using:

```bash
systemctl status docker
```

## Output

Docker was installed successfully and the Docker service is running.
