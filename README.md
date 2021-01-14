# Restaurant orders


## O que foi desenvolvido

A lanchonete Pão na Chapa, possuía um sistema de faturamento dos pedidos dos clientes, que salva o nome da pessoa, o pedido realizado, e dia do atendimento (dia da semana). O projeto consistiu em ajudar a lanchonete a melhorar esse sistema para que ele possibilite extração de relatórios e num segundo momento, a controlar seu estoque.

---

## Desenvolvimento e testes

**Estrutura do repositório**

- No diretório `src/` você vai encontrar os arquivos com todas as classes implementadas e métodos que foram considerados importantes para resolver cada etapa do projeto;

- No diretório `data/` você vai encontrar os arquivos de _log_ que foram utilizados em cada etapa;

- Os testes devem ser implementados nos arquivos do diretório `tests/`.

**Testes**

Para executar os testes, lembre-se de primeiro **ativar o ambiente virtual**, além de também instalar as dependências do projeto. Isso pode ser feito através dos comandos:

```bash
$ python3 -m venv .venv

$ source .venv/bin/activate

$ python3 -m pip install -r dev-requirements.txt
```

**Instalação de dependências**

O arquivo `dev-requirements.txt` contém todos as dependências que foram utilizadas no projeto

Se quiser saber mais sobre a instalação de dependências com `pip`, veja esse [artigo.](https://medium.com/python-pandemonium/better-python-dependency-and-package-management-b5d8ea29dff1)

**Estilo**

Para verificar se você está seguindo o guia de estilo do Python corretamente, execute o comando:

```bash
$ python3 -m flake8
```

## Realizações

Para completar esse projeto foi necessário:

- ler um arquivo csv
- desenvolver estratégias para tirar dias em que pessoas não forma, comidas mais pedidas de cada um, comidas nunca pedidas de cada cliente e quantas vezes cada cliente pediu cada comida
- escrever em um arquivo as respostas
- criar classes com métodos que poderiam ler cada informação de sobre um cliente arbitrário
- criar uma classe que armazena e processa as informações dos pedidos (feito de maneira exaustiva, não faz cache)
- criar uma classe que armazena e processa o estoque, bem como pode não processar um pedido caso não haja ingredientes
- ser capaz de retornar um quantos ingredientes tem que comprar para atingir o estoque mínimo

---

## Realização e Aprendizados

- Treinar algoritmos ajuda na escrita do código e a expressar mais facilmente nossas ideias.
- Algoritmos são muito importantes e nos ajuda a fluir mais na escita do código, com isso quero dizer, conhecer algoritmos te da várias idéias para resolver um problema, te dando o poder de escolher o melhor para aquela situação
