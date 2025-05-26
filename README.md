## Descrição

Este projeto é um dashboard financeiro simples desenvolvido em Python usando Flask. Ele permite cadastrar, visualizar e filtrar movimentações financeiras (receitas, despesas e investimentos), além de gerar gráficos interativos e exportar relatórios em PDF.

O dashboard usa bibliotecas como Pandas para manipulação de dados, Plotly para gráficos interativos, e FPDF para exportação em PDF.

## Funcionalidades

- Cadastro de movimentações financeiras com data, categoria, subcategoria, tipo (Receita, Despesa, Investimento), valor e observação.
- Visualização do resumo financeiro (total de receitas, despesas, investimentos e saldo).
- Gráficos interativos que mostram a evolução financeira ao longo do tempo, distribuição das despesas e comparação entre categorias.
- Filtragem dos dados por período (data inicial e final).
- Exportação de relatório financeiro em PDF com resumo e listagem das movimentações.
- Armazenamento dos dados em arquivo CSV (`data/financeiro.csv`).

## Como rodar

1. Instale as dependências:

```bash
pip install flask pandas plotly fpdf
```

2. Salve o arquivo `app.py` com o código do projeto.

3. Execute o projeto:

```bash
python app.py
```

4. Acesse o dashboard no navegador:

```
http://127.0.0.1:5000/
```

## Estrutura

- `app.py` — Código principal do backend com Flask, manipulação dos dados, geração dos gráficos e páginas HTML via template string.
- `data/financeiro.csv` — Arquivo CSV onde os dados financeiros são salvos.

## Dependências

- Flask
- Pandas
- Plotly
- FPDF



