# ISR_part1

The folder **ansible-scripts** which contains the structure for running ansible automation is stored in the home directory. 

Since this is a custom directory and not the default ansible directory we export the location of our project configuration to be able to run ansible commands from anywhere:

```bash
export ANSIBLE_CONFIG=~/ansible-scripts/ansible.cfg
```