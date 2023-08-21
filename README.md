# ansible

- Install ansible
```bash
sudo apt-add-repository ppa:ansible/ansible
sudo apt update
sudo apt install ansible
```
or
```bash
brew install ansible
```

- Run playbook
  - Install inventory 
    ```bash
    ansible-playbook ./playbook_inventory.yaml -i ./hosts
    ```
    
- Optional:
  - Install helm 
    ```bash
    ansible-playbook ./playbook_helm.yaml -i ./hosts
    ```
    
  - Install k9s 
    ```bash
    ansible-playbook ./playbook_helm.yaml -i ./hosts
    ```
