# Python Insights - Analisando Dados com Python

## Case - Cancelamento de Clientes

Você foi contratado por uma empresa com mais de 800 mil clientes para um projeto de Dados. Recentemente a empresa percebeu que da sua base total de clientes, a maioria são clientes inativos, ou seja, que já cancelaram o serviço.

Precisando melhorar seus resultados ela quer conseguir entender os principais motivos desses cancelamentos e quais as ações mais eficientes para reduzir esse número.

## Instalação

1. Clone o repositório ou baixe os arquivos.
2. Instale as dependências Python:

   ```bash
   pip install -r requirements.txt
   ```

## Como executar

1. Abra o arquivo `inicial.ipynb` no Jupyter Notebook ou Jupyter Lab.
2. Execute as células em ordem para realizar a análise dos dados.

## Dados

- Arquivo de dados: `cancelamentos.csv`
- Fonte: [Google Drive](https://drive.google.com/drive/folders/1uDesZePdkhiraJmiyeZ-w5tfc8XsNYFZ?usp=drive_link)

## Dependências

As dependências estão listadas no arquivo `requirements.txt`:
- pandas: Para manipulação de dados
- plotly: Para visualizações
- openpyxl: Para leitura de arquivos Excel (se necessário)
- nbformat: Para formatação de notebooks
- ipykernel: Para execução de notebooks

## Resultados

O notebook analisa os dados de cancelamentos, remove valores ausentes, calcula estatísticas e gera gráficos para identificar padrões nos cancelamentos.