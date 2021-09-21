# Descrição

Rest API com Python, Flask, com banco de dados SQLAlchemy e JWT que disponibiliza um token de acesso. Possui os métodos GET(listar todas as contas), POST(cadastro de uma conta), POST(login da conta - libera o token), POST(loggout da conta - requer o token), GET(listar todos os usuários e listar usuários por id), POST(cadastrar usuario inserindo os dados: usuario_id, nome, idade e cidade- requer o token), PUT(atualizar usuários - requer o token) e DELETE(deletar usuários por id - requer o token).

Obs: É possível criar contas através do cadastro, dentro de uma conta é possível criar várias redes e dentro de uma rede é possível criar vários usuarios.

# Comandos no terminal para configuração

```bash
python setup.py develop
```

# Rodando a aplicação

```bash
python principal.py
```

# Teste no Postman

<span align="center">
    <img src="https://user-images.githubusercontent.com/85804895/134180792-5753fe9d-3a66-43e6-ac9b-0f3c443565ef.png", width=900>
</span>

<span align="center">
    <img src="https://user-images.githubusercontent.com/85804895/134180926-4e791aab-858b-4ca0-a28d-bbe2716186c0.png", width=900>
</span>

<span align="center">
    <img src="https://user-images.githubusercontent.com/85804895/134181029-01846f66-9288-40ac-b910-7d356cd9e597.png", width=900>
</span>
