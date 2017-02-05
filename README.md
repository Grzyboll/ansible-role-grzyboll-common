ansible-role-grzyboll-common
=========

This is my own role to customize Linux and add some features like ansible syntax in Vim

Requirements
------------

Role Variables
--------------

```yaml
env_home: "{{ ansible_env.HOME }}"
vundle_repo: "https://github.com/VundleVim/Vundle.vim"
bash_git_prompt: "https://github.com/magicmonty/bash-git-prompt"
```

Dependencies
------------

Example Playbook
----------------

```yml
- hosts: local
  roles:
    - role: ansible-role-grzyboll-common 
```

License
-------

BSD

Author Information
------------------
Grzyboll: pokiegogrzyba @gmail.com
