NextDom
=========

Install last version of NextDom


Example Playbook
----------------

Playbook exemple :

    - hosts: all
      gather_facts: no
      roles:
         - role: m4dm4rtig4n.nextdom

How to run it without inventory :

      ansible-galaxy install m4dm4rtig4n.nextdom
      ansible-playbook -i 192.168.X.X, -u ssh_user -p ssh_password playbook.yaml

License
-------

BSD

