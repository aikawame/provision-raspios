# provision-raspios

## インストール

```bash
scp -r ~/src/dotfiles/.ssh raspi:~
ansible-playbook -i hosts site.yml -k --ask-vault-pass
```
