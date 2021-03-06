#ansible-playbook

Using following commands to execute playbooks

```sh
ansible-playbook -i ./hosts --ask-su-pass ./playbooks/<playbooks_name>/main.yaml 
```

Following playbooks are provided: 

1. reboot:
    * reboot all host

2. CSA-START:
    * Configure all host to follow CSA-START security policy

3. logstash:
    * deploy logstash agent 

4. rkhunter:
    * main.yaml: install & configure rkhunter
    * update.yaml: update rkhunter db

5. exim4:
    * Install & configure Exim4 MTA

6. delUser:
    * delete users and home directory

6. chpassword:
    * change user password, use ```mkpasswd --method=SHA-512``` to generate hashed passwrod first

