# provision-raspios

## 初回コマンド

```bash
ansible-playbook -i hosts site.yml -k --ask-vault-pass
```

## 2回目以降のコマンド

```bash
ansible-playbook -i hosts site.yml --ask-vault-pass
```
