```
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt-get --yes install ansible 
ansible-galaxy install gantsign.oh-my-zsh
sudo ansible-pull -U https://github.com/Zeulewan/ansible_preset.git os.yml
ansible-pull -U https://github.com/Zeulewan/ansible_preset.git userland.yml
```
