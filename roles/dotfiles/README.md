Dotfiles
=========

This role takes care of my dotfiles


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role.
Variable | Default | Description
--- | --- | ---
`dotfiles` | bashrc, vimrc, zshrc | List of dotfiles
`home_dir` | /home/araszka | Home directory where dotfiles will be stored
`backup_dir` | /home/araszka/.dotfiles_backup | Place where dotfiles are backed-up




Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - dotfiles

License
-------

BSD

