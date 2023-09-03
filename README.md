# Dev Environment Setup

Build the Ubuntu docker container with the Ansible Playbook included
```bash
./build-container
```

Run bash from the docker container in interactive mode
```bash
sudo docker run --rm -it new-computer bash
```

Run the playbook passing the entry YAML file
```bash
ansible-playbook setup.yml
```
