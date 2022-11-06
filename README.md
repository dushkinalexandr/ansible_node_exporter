# ansible_node_exporter
Install node_exporter

- Create user
- Download/install/configure/start node_exporter
- Add firewall rule


Run playbook for host:
```
ansible-playbook -i hosts playbook.yml
```

Run automaticaly:
```sh
bash ./run_ansible.sh
```

Check:
```
curl http://fedora35:9100/metrics | less
```
