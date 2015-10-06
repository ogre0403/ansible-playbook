#ansible-playbook

Using following commands to execute playbooks

```sh
ansible-playbook -i ./hosts --ask-su-pass ./playbooks/<playbooks_name>/main.yaml 
```

Following playbooks are provided: 

1. reboot.yaml:
    * reboot all host

2. CSA-START.yaml
    * Configure all host to follow CSA-START security policy

3. logstash.yaml
    * deploy logstash agent 

4. rkhunter
    * install & configure rkhunter
