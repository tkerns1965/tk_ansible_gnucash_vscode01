# tk_ansible_gnucash_vscode01

For use on bare Ubuntu 18.04.3 Desktop

1.  sudo apt-add-repository -y ppa:ansible/ansible
2.  sudo apt install -y ansible git python-pexpect
3.  git clone -b update01 --single-branch https://github.com/tkerns1965/tk_ansible_gnucash_vscode01.git
4.  cd tk_ansible_gnucash_vscode01/
5.  cp roles/gnucash_vscode01/vars/private.yml.sample roles/gnucash_vscode01/vars/private.yml
6.  nano roles/gnucash_vscode01/vars/private.yml
7.  ansible-playbook -K gnucash_vscode01.yml
