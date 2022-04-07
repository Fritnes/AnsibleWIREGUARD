Role "AnsibleWIREGUARD"
=========

https://github.com/ngoduykhanh/wireguard-ui

Role Variables
--------------

docker_folder: "/opt"
version: "3"
wggui_container_name: "wggui"
WGUI_USERNAME: "admin"
WGUI_PASSWORD: "admin"


Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: AnsibleWIREGUARD }

Author Information
------------------

fritnes
https://github.com/Fritnes
