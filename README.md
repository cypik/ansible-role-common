<!-- This file was automatically generated by the `geine`. Make all changes to `README.yaml` and run `make readme` to rebuild this file. -->

<p align="center"> <img src="https://user-images.githubusercontent.com/50652676/62451340-ba925480-b78b-11e9-99f0-13a8a9cc0afa.png" width="100" height="100"></p>

<h1 align="center">
    Ansible Role Common
</h1>


<p align="center" style="font-size: 1.2rem;">
    This ansible role install common packages On Ubuntu, CentOS.
     </p>

We eat, drink, sleep and most importantly love **DevOps**. DevOps always promotes automation and standardisation. While setting up various environments like local, dev, testing, production, etc. it is critical to maintain the same environment across. This can easily be achieved using automating the environment setup & installation with the help of ansible-playbooks.

Smaller roles are created for each environment elements; which also include tasks & tests. These roles can then be grouped together in [Ansible-Role-Common](https://docs.ansible.com/ansible/latest/user_guide/playbooks_intro.html) to achieve the desired yet consistent results.

## Table of Contents
- [What Includes](#What-Includes)
- [Example Playbook](#Example-Playbook)
- [Variables](#Variables)
- [License](#license)

## What Includes

Following things includes in this role:

- ntp
- openssl
- git
- telnet
- figlet
- git-core
- htop
- wget
- python3-pip
- zip
- vim
- vim-common
- curl
- rsyslog
- libjson-xs-perl







## Example Playbook

**IMPORTANT:** Since the `master` branch used in `source` varies based on new modifications, we suggest that you use the release versions [here](https://github.com/cypik/ansible-role-common/releases).


```yaml
  - hosts: localhost
    remote_user: root
    become: true
    roles:
      - ansible-role-common
```


## Variables

```yaml
  zsh_theme: steeef
  state: present
  aws: true

  user: false
  username: ubuntu

```
## About us

At [cypik][website], we offer expert guidance, implementation support and services to help organisations accelerate their journey to the cloud. Our services include docker and container orchestration, cloud migration and adoption, infrastructure automation, application modernisation and remediation, and performance engineering.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/cypik/ansible-role-common/blob/master/LICENSE) file for details.






