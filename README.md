utilisateur-formation-ansible
=========

Role de formation

Requirements
------------

Aucun

Role Variables
--------------

suffixe_utilisateur : suffixe a appliquer a l'utilisateur, il sera nommé formation-{{ suffixe_utilisateur}}

uid_utilisateur: uid de l'utilisateur, 2500 par défaut

Dependencies
------------

aucune

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - name: ugiraud.utilisateur_formation_ansible
          vars:
            suffixe_utilisateur: 1

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
