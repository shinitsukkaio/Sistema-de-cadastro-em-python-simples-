#  Sistema de Cadastro e Login

Sistema simples de cadastro e login de usuários feito em **Python**, rodando direto no terminal.

##  Funcionalidades

- **Cadastrar usuário** — salva nome, e-mail, idade, usuário e senha
- **Fazer login** — valida usuário e senha cadastrados
- **Listar usuários** — exibe todos os usuários cadastrados
- **Sair** — encerra o programa

##  Como executar

Você precisa apenas do **Python 3** instalado. Nenhuma biblioteca extra é necessária.

```bash
python main.py
```

##  Como funciona

O programa exibe um **menu em loop** onde você escolhe uma opção digitando o número correspondente:

```
1 - Cadastrar usuário
2 - Fazer login
3 - Listar usuários
4 - Sair
```

Os dados ficam salvos **apenas enquanto o programa está rodando** — ao fechar, tudo é apagado (sem banco de dados ou arquivos).

##  Observações

- Os dados **não são persistidos** entre execuções
- As senhas são armazenadas em texto puro (sem criptografia)
- Projeto indicado para fins de **aprendizado**

##  Tecnologias utilizadas

- **Python 3**
