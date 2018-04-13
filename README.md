# Ansible Role: RabbitMQ

[![Build Status](https://travis-ci.org/evolic/ansible-role-rabbitmq.svg?branch=master)](https://travis-ci.org/geerlingguy/ansible-role-rabbitmq)

Installs RabbitMQ on Linux.

## Requirements

(Red Hat / CentOS only) Requires the EPEL repository, which can be installed with the `geerlingguy.repo-epel` role.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    TODO
    Unbuntu 16.04 and CentOS operating systems need to be checked.
    [x]   

TODO.

## Dependencies

None.

## Example Playbook

    - hosts: rabbitmq
      roles:
        - name: geerlingguy.repo-epel
          when: ansible_os_family == 'RedHat'
        - evolic.rabbitmq

## License

MIT / BSD

## Author Information

This role was created in 2018 by [Tomasz Kuter](http://tomaszkuter.com/), based on work of [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
