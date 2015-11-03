# Ansible apt-cyg module

## Require

apt-cyg: https://github.com/transcode-open/apt-cyg

## Usage

This is a easier usage.

```
$ git clone https://github.com/naokirin/ansible-apt-cyg-module.git
$ cd ansible-apt-cyg-module
$ cp -r library /your/playbook/path
```

**your-playbook.yml**
  ```
  ---
  - hosts: cygwin
    tasks:
      - name: install git
        apt-cyg: name=git
  ```
