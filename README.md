# jakenpo-python-flask

Jogo simples de pedra, papel e tesoura escrito em Python com o framework Flask.


# Código

A lógica fica no arquivo principal, que renderiza uma página de marcação e usa arquivos estáticos da pasta de assets.

O arquivo principal declara duas funções ligadas a requisições. A primeira apenas renderiza a tela onde o jogador escolhe a opção e envia por formulário. A segunda recebe a escolha, sorteia a opção do computador, compara as duas e devolve:

- a opção do computador;
- quem venceu.

(A página já sabe qual foi a escolha do jogador)


# Execução

Depois de clonar o repositório, instale o framework:
```
pip install flask
```

E execute:
```
python index.py
```

O jogo abre no navegador pelo endereço da máquina local na porta configurada.


# Demonstração
Há uma gravação do jogo em uso.



> [!NOTE]
> Os nomes de arquivo e pasta foram mantidos como no projeto original.

# Requisitos

As dependências estão listadas no arquivo de requisitos do projeto.


# Porta da aplicação

A porta foi alterada em novembro de 2024 para 7000.