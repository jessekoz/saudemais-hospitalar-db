# 🏥 SaúdeMais Hospitalar - Banco de Dados Relacional

Este repositório contém a modelagem e implementação de um **banco de dados relacional em MySQL** desenvolvido para simular a gestão hospitalar da instituição fictícia **SaúdeMais Hospitalar**.  
O projeto foi criado com fins **acadêmicos** e de **aprendizado em SQL e modelagem de dados**.

---

## 📌 Objetivo
O objetivo deste projeto é fornecer um ambiente de simulação para gerenciamento hospitalar, permitindo o estudo e prática de conceitos de banco de dados, como:
- Modelagem de tabelas e relacionamentos.
- Criação de **chaves primárias e estrangeiras**.
- Inserção e manipulação de dados.
- Consultas SQL para análise de informações.

---

## 🗂 Estrutura do Banco de Dados
O banco contempla os principais módulos de um sistema hospitalar:

- **CLIENTE** → Cadastro de hospitais, clínicas e parceiros.  
- **ENDERECO** → Localização dos clientes/parceiros.  
- **MARCAS** → Registro de marcas de equipamentos médicos.  
- **EQUIPAMENTOS** → Equipamentos vinculados aos clientes e marcas.  
- **PRODUTOS** → Produtos hospitalares e insumos.  
- **PRECO_PRODUTO** → Controle de preços.  
- **FORNECEDOR** → Fornecedores de produtos.  
- **ESTOQUE** → Controle de quantidade de produtos disponíveis.  
- **PEDIDO** → Registro de pedidos feitos.  
- **ITEM_PEDIDO** → Itens de cada pedido.  
- **PAGAMENTO** → Gestão dos pagamentos.  
- **MANUTENCAO_EQUIPAMENTO** → Histórico de manutenções preventivas e corretivas.  

---

## 📊 Diagrama Entidade-Relacionamento (ER)
> 🔹 <img width="1645" height="583" alt="image" src="https://github.com/user-attachments/assets/426e5602-50ca-481a-b701-62df3b387d15" />

```md
![Diagrama ER](diagrama.png)




