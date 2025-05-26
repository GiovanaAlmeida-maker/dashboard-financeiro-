Dashboard Financeiro em Flask
Descrição
Projeto backend em Python com Flask que simula um dashboard financeiro para controle de finanças pessoais ou empresariais. Permite o cadastro de movimentações (receitas, despesas e investimentos), geração automática de gráficos interativos e exportação de relatórios em PDF.

Funcionalidades
Cadastro de movimentações financeiras com data, categoria, subcategoria, tipo, valor e observação.

Visualização de indicadores financeiros (totais de receitas, despesas, investimentos e saldo).

Gráficos interativos gerados com Plotly (linha temporal, pizza para despesas e barras por categoria).

Filtro dos dados por período (datas).

Exportação de relatório financeiro completo em PDF.

Tecnologias utilizadas
Python 3

Flask

Pandas

Plotly

FPDF

Instalação e execução
Clone o projeto ou crie o arquivo app.py com o código fornecido.

(Opcional) Crie um ambiente virtual:

bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
Instale as dependências:

bash
Copiar
Editar
pip install flask pandas plotly fpdf
Execute o servidor Flask:

bash
Copiar
Editar
python app.py
Acesse no navegador:

cpp
Copiar
Editar
http://127.0.0.1:5000/
Estrutura dos dados
Os dados são armazenados no arquivo CSV data/financeiro.csv com as colunas:

Data (YYYY-MM-DD)

Categoria

Subcategoria

Tipo (Receita, Despesa, Investimento)

Valor (decimal)

Observação (texto opcional)

Uso
Utilize o menu para cadastrar novas movimentações financeiras.

Visualize os indicadores e gráficos na página inicial.

Aplique filtros por período para análises específicas.

Exporte relatórios em PDF para consulta ou impressão.

