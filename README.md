# 📊 Projeto: Modelagem de Dados no Power BI – Esquema Estrela
📌 Descrição do Projeto
Este projeto faz parte de um desafio prático de modelagem de dados no Power BI, utilizando um esquema estrela. O objetivo foi transformar a tabela única Financial Sample em um modelo dimensional eficiente, criando tabelas fato e dimensão para melhor organização e análise dos dados.


## 🏗 Modelagem de Dados
A modelagem seguiu o Esquema Estrela, onde a tabela fato (F_Vendas) centraliza os dados transacionais, e as tabelas dimensão (D_Produtos, D_Calendário, D_Descontos, etc.) fornecem informações contextuais.


## 📌 Tabelas Criadas:
✅ F_Vendas (Fato) – Contém os registros de vendas, com chaves para as tabelas dimensão.  
✅ D_Produtos – Informações sobre os produtos vendidos.  
✅ D_Produtos_Detalhes – Detalhamento de preços e unidades vendidas.  
✅ D_Descontos – Faixas e percentuais de desconto.  
✅ D_Detalhes – Informações adicionais de vendas.  
✅ D_Calendário – Criada com DAX (CALENDAR()) para suporte a análises temporais.  


## 🔄 Processo de Construção
1️⃣ Importação da Tabela Financial Sample – Extração dos dados originais.  
2️⃣ Criação das Tabelas Dimensão e Fato – Organização dos dados em um modelo estrela.  
3️⃣ Transformações no Power Query – Limpeza e ajuste das colunas.  
4️⃣ Criação de Medidas e Cálculos com DAX – Como médias, máximos e mínimos de vendas.  
5️⃣ Relacionamento das Tabelas – Conexão entre fatos e dimensões.  
6️⃣ Visualização e Testes – Construção de dashboards para validar os dados.  
