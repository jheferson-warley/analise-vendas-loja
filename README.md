# 📊 Análise de Vendas - Loja

Este projeto realiza a extração, tratamento e visualização de dados de uma base de vendas de uma loja, utilizando Python, MySQL e bibliotecas de análise de dados.

## 📌 Funcionalidades
- Conexão com banco de dados MySQL para consulta de informações sobre clientes, produtos e vendas.
- Análise e extração de insights através de consultas SQL.
- Geração de relatório Excel consolidado com os dados.
- Visualização gráfica dos resultados utilizando Plotly e Seaborn.

## 🛠 Tecnologias Utilizadas
- Python
- MySQL
- Pandas
- Matplotlib
- Seaborn
- Plotly

## 🔧 Como Executar o Projeto
1. **Instale as dependências**:
   ```bash
   pip install mysql-connector-python pandas matplotlib seaborn plotly
   ```
2. **Configure o banco de dados MySQL**:
   - Crie um banco chamado `loja_vendas`.
   - Insira as tabelas `clientes`, `produtos` e `vendas`.
3. **Edite as credenciais no código** caso necessário:
   ```python
   conn = mysql.connector.connect(
       host='localhost',       
       user='root',            
       password='',            
       database='loja_vendas',
       port=3306  
   )
   ```
4. **Execute o script**:
   ```bash
   python index.py
   ```
5. O relatório será gerado como `relatorio_loja_vendas.xlsx`.
6. Os gráficos serão exibidos automaticamente no navegador.

## 📊 Gráficos Gerados
- **Total de vendas por produto** (barras)
  ![Captura de tela 2025-03-17 161722](https://github.com/user-attachments/assets/49339dc9-13fb-4457-9635-94e8e6281a42)

- **Top 10 clientes por gasto** (barras)
  ![Captura de tela 2025-03-17 161739](https://github.com/user-attachments/assets/dfc800da-b879-404f-8bbf-924dea0b84ac)

- **Receita diária** (linha temporal)
  ![Captura de tela 2025-03-17 161750](https://github.com/user-attachments/assets/085e24b9-ccb8-481c-8dca-39ead1a68312)


## 📜 Estrutura do Projeto
```
📂 projeto-loja-vendas
├── index.ipynb
├── README.md
└── relatorio_loja_vendas.xlsx (gerado após execução)
```

## 🏆 Contribuição
Fique à vontade para sugerir melhorias e contribuir com o projeto! 🚀

## 📄 Licença
Este projeto está sob a licença MIT.

