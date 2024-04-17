# ansible-ssh-user
Run playbook for all host and user

```ansible-playbook -i hosts example.yaml```

Run playbook for specific host group

```ansible-playbook -i hosts example.yaml -l web_server```

Run playbook for specific user tag

```ansible-playbook -i hosts example.yaml --tags nhantv12```
