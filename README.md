# Sistema de Vendas e Gestão Online

Aplicação web desenvolvida em Python utilizando Streamlit, Pandas e Plotly para cadastrar vendas, visualizar registros e acompanhar o faturamento por meio de um dashboard interativo.

## Funcionalidades

* Cadastro de vendas por meio de um formulário na barra lateral.
* Seleção da data, vendedor e produto.
* Registro da quantidade e do valor da venda.
* Salvamento automático das vendas no arquivo CSV.
* Exibição das vendas cadastradas em uma tabela interativa.
* Visualização do faturamento total.
* Gráfico de barras com os valores das vendas por vendedor e produto.
* Gráfico de pizza com a participação dos produtos no faturamento.

## Tecnologias utilizadas

* **Python** 
* **Streamlit:** criação da interface web.
* **Pandas:** manipulação e organização dos dados.
* **Plotly Express:** criação de gráficos interativos.
* **CSV:** armazenamento dos registros de vendas.

## Estrutura do projeto

```text
sistema-de-vendas/
├── main.py
├── vendas.csv
└── README.md
```

* `main.py`: código principal da aplicação.
* `vendas.csv`: arquivo que armazena os registros de vendas.
* `README.md`: documentação do projeto.

## Pré-requisitos

* Python instalado no computador.
* Visual Studio Code.
* Prompt de Comando (CMD) ou terminal.
* Arquivos `main.py` e `vendas.csv` na mesma pasta.

## Instalação

### 1. Abra o CMD na pasta do projeto

Abra a pasta do projeto no Explorador de Arquivos do Windows. Na barra de endereço, digite `cmd` e pressione Enter.

### 2. Instale as bibliotecas necessárias

Execute o  comando no CMD:

```bash
pip install streamlit pandas plotly
```

**Importante:** após a instalação das bibliotecas, reinicie o computador antes de continuar.

### 3. Execute o sistema

Após reiniciar o computador, abra novamente o CMD na pasta do projeto e execute:

```bash
streamlit run main.py
```

O Streamlit iniciará a aplicação e exibirá um endereço local no terminal, geralmente:

```text
http://localhost:8501
```

Abra esse endereço no navegador para acessar o sistema.

Para encerrar a aplicação, volte ao terminal e pressione `Ctrl + C`.

## Como utilizar

1. Abra o sistema no navegador.
2. Na barra lateral, selecione a data da venda.
3. Escolha o vendedor e o produto.
4. Informe a quantidade e o valor da venda.
5. Clique em **Cadastrar venda**.
6. Confira a mensagem de confirmação e visualize o registro na tabela.
7. Consulte o dashboard para acompanhar o faturamento e os gráficos.

## Armazenamento dos dados

As vendas são carregadas do arquivo `vendas.csv`. Quando uma nova venda é cadastrada, o sistema adiciona os dados à tabela e atualiza o arquivo CSV.

Mantenha o arquivo `vendas.csv` na mesma pasta do `main.py` e faça cópias de segurança periódicas para evitar a perda dos registros.

## Opções disponíveis

**Vendedores:**

* Ana
* Bruno
* Carla

**Produtos:**

* Notebook
* Celular
* Fone

Essas opções podem ser modificadas diretamente no código `main.py`.

## Dashboard

O dashboard apresenta:

* **Faturamento total:** soma dos valores registrados na coluna `valor`.
* **Gráfico de barras:** compara os valores das vendas por vendedor e produto.
* **Gráfico de pizza:** apresenta a participação dos produtos no faturamento.

## Publicação do projeto

O sistema pode ser publicado na internet utilizando o GitHub para armazenar o código e o Streamlit Community Cloud para hospedar a aplicação.

Para isso, envie ao repositório os arquivos `main.py` e `vendas.csv`. Recomenda-se também criar um arquivo `requirements.txt` com as dependências do projeto:

```text
streamlit
pandas
plotly
```

No Streamlit Community Cloud, selecione o repositório, a branch `main` e informe `main.py` como arquivo principal.

---

**Projeto de estudo:** Sistema de Vendas desenvolvido com Python.


