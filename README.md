NextDom
=========

Install last version of NextDom


Install with playbook
----------------

Playbook exemple :

    - hosts: all
      gather_facts: no
      roles:
         - role: m4dm4rtig4n.nextdom

How to run it without inventory :

      ansible-galaxy install m4dm4rtig4n.nextdom
      ansible-playbook -i 192.168.X.X, -u root -k playbook.yaml

Install without playbook (Standalone)
----------------

    ansible-galaxy install m4dm4rtig4n.nextdom
    ansible all -i 192.168.X.X, -u root -k -m include_role -a name=m4dm4rtig4n.nextdom
    
License
-------

BSD

