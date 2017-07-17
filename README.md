Role Name
=========

Downloads & optionally compares hash & installs *.deb file.

Requirements
------------

No requirements.


Role Variables
--------------

Mandatory variables:
- url_path
- deb_file

Optional variable: deb_checksum


Dependencies
------------

No dependencies.

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: Alex2357.deb-install, url_path: 'https://www.scootersoftware.com', deb_file: 'bcompare-4.2.2.22384_amd64.deb', deb_checksum: 'sha256:eaf3bae9c3a29c6b7137e7a9b57ecb9dc4fdd26389dfe1a5c0c0ddd90a0e1a53' }

    - hosts: servers
      roles:
         - { role: Alex2357.deb-install, url_path: 'https://www.scootersoftware.com', deb_file: 'bcompare-4.2.2.22384_amd64.deb' }         

License
-------

BSD

