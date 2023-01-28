# docker-setup-using-ansible

- ## Create `hosts` inventory files
- ## Run Commands

    ```shell
        ansible-galaxy install geerlingguy.docker

        ansible-galaxy install andrewrothstein.docker-compose
        
        ansible-playbook -i hosts.yaml docker-playbook.yaml
    ```
    