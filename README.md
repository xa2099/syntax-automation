## Settings

All settings are located in the `group_vars/all.yml`.

## Dependancies

The playbook uses Docker configuration file from `https://gist.github.com/yassineselmi/1d929dced4e069fb338b2b4fbd8c5a0e`. 
Any changes to that file will reflect on the next playbook run.

A pair of public and private keys needs to exist. Make sure to point to the public key in the `group_vars/all.yml` file and
the private key in the `ansible.cfg` file.
