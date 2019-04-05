# SSH-authorized_keys
Ansible Moduel authorized_keys
https://docs.ansible.com/ansible/latest/modules/authorized_key_module.html

- name: Set authorized keys taken from url
  authorized_key:
    user: charlie
    state: present
    key: https://github.com/charlie.keys
