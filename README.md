almaops.ct_rabbitmq
=========

RabbitMQ in docker container

Description
-----------

This role deploys a docker container with RabbitMQ.

Example
-------

    - hosts:
        - rmq
      become: true
      tags:
        - rabbitmq
      roles:
        - role: almaops.ct_rabbitmq

Install
-------

This role can be installed from [Ansible Galaxy](https://galaxy.ansible.com/):

`ansible-galaxy install almaops.ct_rabbitmq`

License
-------

MIT
