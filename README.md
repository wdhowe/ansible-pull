# ansible-pull

System configuration using ansible-pull.

`Made for Ubuntu 22.04`.

## Getting Started

- Install ansible

```bash
sudo apt install ansible
```

- Run the pull playbook

```bash
sudo ansible-pull --url https://github.com/wdhowe/ansible-pull.git
```

- Run the pull playbook, override the 'user' variable used in various roles.

```bash
sudo ansible-pull --url https://github.com/wdhowe/ansible-pull.git --extra-vars "user=USERNAME"
```
