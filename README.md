#ansible-playbook

Using following commands to execute playbooks

```sh
ansible-playbook -i ./hosts --ask-su-pass ./playbooks/<playbooks_name>.yaml 
```

Following playbooks are provided: 
1. reboot.yaml:
    * reboot all host
2. CSA-START.yaml
    * Configure all host to follow CSA-START security policy
3. deploy_logstash.yaml
    * deploy logstash agent 
