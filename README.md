# workspace-bootstrap
WIP WIP WIP
IaC for workstation bootstrap using Ansible

tests:
```
docker run -it --rm -v $(pwd):/ansible -w /ansible ubuntu:20.04 bash -c 'apt update && apt install -y ansible && ansible-playbook -i inventory/ play.yml --check && /bin/sh'
```
