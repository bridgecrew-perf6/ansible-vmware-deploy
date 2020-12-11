# ansible-vmware-deploy


Prepations:
```
pip3 install -r requirements.txt

ansible-galaxy collection install -r collections.yaml

```

Now run

```
ansible-playbook -i input.json playbook.yaml
```

You will be prompted with username and password for the vCenter server.

Note: Due to VMware you might be required to connect the network interface(s) on one or more vms for it to complete.
Otherwise set wait_for_ip_address: False
