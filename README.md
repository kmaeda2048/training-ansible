# training-ansible

```shell
dnf install -y epel-release
dnf install -y --enablerepo epel-playground ansible
ansible --version

git clone git@github.com:kmaeda2048/training-ansible.git
cd training-ansible

ansible-playbook site.yml --check
ansible-playbook site.yml
```

