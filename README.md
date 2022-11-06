# ansible_node_exporter
Install node_exporter

- Create user
- Download/install/configure/start node_exporter
- Add firewall rule

Playbook: main.yml

Run playbook for host:
ansible-playbook -i hosts -l fedora35 main.yml
