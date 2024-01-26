# ansible-pull

System configuration using ansible-pull.

`Made for Ubuntu 23.10`

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

- Run locally when repo is cloned

  ```bash
  sudo ansible-playbook local.yml
  ```
