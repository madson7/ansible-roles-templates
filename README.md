Exemplo de uso:

Clone o repositório
```
git clone https://github.com/madson7/ansible-roles-templates.git
cd ansible-roles-templates
```

Edite o inventario conforme a necessidade
```
vi inventario.ini
```

Use todas as roles disponíveis ou deixe o playbook main conforme a necessidade
```
ansible-playbook -i inventario.ini main.yml
```