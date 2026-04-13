<div style="text-align: center">

[![Flatcar OS](https://img.shields.io/badge/Flatcar-Website-blue?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4NCjwhLS0gR2VuZXJhdG9yOiBBZG9iZSBJbGx1c3RyYXRvciAyNi4wLjMsIFNWRyBFeHBvcnQgUGx1Zy1JbiAuIFNWRyBWZXJzaW9uOiA2LjAwIEJ1aWxkIDApICAtLT4NCjxzdmcgdmVyc2lvbj0iMS4wIiBpZD0ia2F0bWFuXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4Ig0KCSB2aWV3Qm94PSIwIDAgODAwIDYwMCIgc3R5bGU9ImVuYWJsZS1iYWNrZ3JvdW5kOm5ldyAwIDAgODAwIDYwMDsiIHhtbDpzcGFjZT0icHJlc2VydmUiPg0KPHN0eWxlIHR5cGU9InRleHQvY3NzIj4NCgkuc3Qwe2ZpbGw6IzA5QkFDODt9DQo8L3N0eWxlPg0KPHBhdGggY2xhc3M9InN0MCIgZD0iTTQ0MCwxODIuOGgtMTUuOXYxNS45SDQ0MFYxODIuOHoiLz4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik00MDAuNSwzMTcuOWgtMzEuOXYxNS45aDMxLjlWMzE3Ljl6Ii8+DQo8cGF0aCBjbGFzcz0ic3QwIiBkPSJNNTQzLjgsMzE3LjlINTEydjE1LjloMzEuOVYzMTcuOXoiLz4NCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik02NTUuMiw0MjAuOXYtOTUuNGgtMTUuOXY5NS40aC0xNS45VjI2MmgtMzEuOVYxMzQuOEgyMDkuNFYyNjJoLTMxLjl2MTU5aC0xNS45di05NS40aC0xNnY5NS40aC0xNS45djMxLjINCgloMzEuOXYxNS44aDQ3Ljh2LTE1LjhoMTUuOXYxNS44SDI3M3YtMTUuOGgyNTQuOHYxNS44aDQ3Ljh2LTE1LjhoMTUuOXYxNS44aDQ3Ljh2LTE1LjhoMzEuOXYtMzEuMkg2NTUuMnogTTQ4Ny44LDE1MWg3OS42djMxLjgNCgloLTIzLjZ2NjMuNkg1MTJ2LTYzLjZoLTI0LjJMNDg3LjgsMTUxTDQ4Ny44LDE1MXogTTIzMywyMTQuNlYxNTFoNjMuN3YyMy41aC0zMS45djE1LjhoMzEuOXYyNC4yaC0zMS45djMxLjhIMjMzVjIxNC42eiBNMzA1LDMxNy45DQoJdjE1LjhoLTQ3Ljh2MzEuOEgzMDV2NDcuN2gtOTUuNVYyODYuMUgzMDVMMzA1LDMxNy45eiBNMzEyLjYsMjQ2LjRWMTUxaDMxLjl2NjMuNmgzMS45djMxLjhMMzEyLjYsMjQ2LjRMMzEyLjYsMjQ2LjRMMzEyLjYsMjQ2LjR6DQoJIE00NDguMywzMTcuOXY5NS40aC00Ny44di00Ny43aC0zMS45djQ3LjdoLTQ3LjhWMzAyaDE1Ljl2LTE1LjhoOTUuNVYzMDJoMTUuOUw0NDguMywzMTcuOXogTTQ0MCwyNDYuNHYtMzEuOGgtMTUuOXYzMS44aC0zMS45DQoJdi03OS41aDE1Ljl2LTE1LjhoNDcuOHYxNS44aDE1Ljl2NzkuNUg0NDB6IE01OTEuNiwzMTcuOXY0Ny43aC0xNS45djE1LjhoMTUuOXYzMS44aC00Ny44di0zMS43SDUyOHYtMTUuOGgtMTUuOXY0Ny43aC00Ny44VjI4Ni4xDQoJaDEyNy4zVjMxNy45eiIvPg0KPC9zdmc+DQo=)](https://www.flatcar.org/)
[![Discord](https://img.shields.io/badge/Discord-Chat%20with%20us!-5865F2?logo=discord)](https://discord.gg/PMYjFUsJyq)
[![Matrix](https://img.shields.io/badge/Matrix-Chat%20with%20us!-green?logo=matrix)](https://app.element.io/#/room/#flatcar:matrix.org)
[![Slack](https://img.shields.io/badge/Slack-Chat%20with%20us!-4A154B?logo=slack)](https://kubernetes.slack.com/archives/C03GQ8B5XNJ)
[![Twitter Follow](https://img.shields.io/twitter/follow/flatcar?style=social)](https://x.com/flatcar)
[![Mastodon Follow](https://img.shields.io/badge/Mastodon-Follow-6364FF?logo=mastodon)](https://hachyderm.io/@flatcar)
[![Bluesky](https://img.shields.io/badge/Bluesky-Follow-0285FF?logo=bluesky)](https://bsky.app/profile/flatcar.org)
[![OpenSSF Best Practices](https://www.bestpractices.dev/projects/10926/badge)](https://www.bestpractices.dev/projects/10926)

</div>

# toolbox - bring your tools with you

toolbox is a small script that launches a container to let you bring in your favorite debugging or admin tools.

There are currently two scripts that live within this repository:
 - toolbox: designed for Container Linux, uses rkt and systemd-nspawn
 - rhcos-toolbox: designed for Red Hat CoreOS, uses podman

## Usage

```
$ /usr/bin/toolbox
Spawning container core-fedora-latest on /var/lib/toolbox/core-fedora-latest.
Press ^] three times within 1s to kill container.
[root@localhost ~]# dnf -y install tcpdump
...
[root@localhost ~]# tcpdump -i ens3
tcpdump: verbose output suppressed, use -v or -vv for full protocol decode
listening on ens3, link-type EN10MB (Ethernet), capture size 65535 bytes
```

## Advanced Usage

### Use a custom image

toolbox uses a Fedora-based userspace environment by default, but this can be changed to any Docker image. Simply override environment variables in `$HOME/.toolboxrc`:

#### toolbox

```
core@core-01 ~ $ cat ~/.toolboxrc
TOOLBOX_DOCKER_IMAGE=ubuntu-debootstrap
TOOLBOX_DOCKER_TAG=14.04
core@core-01 ~ $ toolbox
Spawning container core-ubuntu-debootstrap-14.04 on /var/lib/toolbox/core-ubuntu-debootstrap-14.04.
Press ^] three times within 1s to kill container.
root@core-01:~# apt-get update && apt-get install tcpdump
```

#### rhcos-toolbox

```
core@core-01 ~ $ cat ~/.toolboxrc
REGISTRY=registry.redhat.io
IMAGE=rhel7/rhel-tools:latest
core@core-01 ~ $ toolbox
Spawning a container 'toolbox-test' with image 'registry.redhat.io/rhel7/rhel-tools:latest'
```

### Automatically enter toolbox on login

Set an `/etc/passwd` entry for one of the users to `/usr/bin/toolbox`:

```sh
useradd bob -m -p '*' -s /usr/bin/toolbox -U -G sudo,docker,rkt
```

Now when SSHing into the system as that user, toolbox will automatically be started:

```
$ ssh bob@hostname.example.com
Container Linux by CoreOS alpha (1284.0.0)
...
Spawning container bob-fedora-latest on /var/lib/toolbox/bob-fedora-latest.
Press ^] three times within 1s to kill container.
[root@localhost ~]# dnf -y install emacs-nox
...
[root@localhost ~]# emacs /media/root/etc/systemd/system/docker.service
```

## Bugs

Please use the [Flatcar issue tracker][bugs] to report all bugs, issues, and feature requests.

[bugs]: https://github.com/flatcar/Flatcar/issues/new

---

## Community & Project Documentation

- [Contributing Guidelines](CONTRIBUTING.md) — How to contribute, find issues, and submit pull requests
- [Code of Conduct](CODE_OF_CONDUCT.md) — Standards for respectful and inclusive community participation
- [Security Policy](SECURITY.md) — How to report vulnerabilities and security-related information
- [Maintainers](MAINTAINERS.md) — Current project maintainers and their responsibilities
- [Governance](GOVERNANCE.md) — Project governance model, decision-making process, and roles
