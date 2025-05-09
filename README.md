
# 🗂️ Projeto de Banco de Dados SQLite

Este projeto demonstra o uso do SQLite3 em Python para:

✅ Criar um banco de dados relacional (`empresa.db`)  
✅ Criar tabelas com chaves primárias e estrangeiras  
✅ Inserir dados nas tabelas  
✅ Realizar consultas simples e avançadas (JOINs, WHERE, ORDER BY)  
✅ Finalizar com boas práticas e comentários detalhados  

## 🛠️ Estrutura do notebook

O notebook está dividido em etapas:

### 1️⃣ Conexão ao banco de dados

- Conectar ao arquivo `empresa.db`  
- Ativar a integridade referencial (`PRAGMA foreign_keys = ON`)

### 2️⃣ Criação de tabelas

- Departamentos  
- Funcionarios  
- Projetos

### 3️⃣ Inserção de dados

- Popula as tabelas com dados simulados

### 4️⃣ Consultas

✅ Listagem simples de funcionários  
✅ JOIN de Funcionários + Departamentos  
✅ Consulta com WHERE + ORDER BY  
✅ JOIN dupla: Projetos + Funcionários + Departamentos

### 5️⃣ Finalização

- Fechamento da conexão

## ▶️ Como rodar este notebook

1️⃣ Clone o repositório:

```bash
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
```

2️⃣ Abra o notebook no Google Colab ou Jupyter Notebook.

3️⃣ Execute as células uma a uma para ver o funcionamento completo.

## 🔎 Exemplo de saída (resumo)

```
Conexão criada e FOREIGN KEYS ativadas.
Tabelas criadas com sucesso!
Dados inseridos com sucesso!

Lista de Funcionários:
(1, 'Ana Costa', 'Analista', 3500.0, 2)
(2, 'Carlos Lima', 'Gerente', 7000.0, 1)
(3, 'Paula Souza', 'Assistente', 2500.0, 3)

Funcionários com seus Departamentos:
('Ana Costa', 'Analista', 'Tecnologia')
('Carlos Lima', 'Gerente', 'Recursos Humanos')
('Paula Souza', 'Assistente', 'Financeiro')

Funcionários com salário acima de 3000, ordenados por salário DESC:
('Carlos Lima', 7000.0)
('Ana Costa', 3500.0)

Projetos com seus responsáveis e departamentos:
('Projeto Alpha', 'Ana Costa', 'Tecnologia')
('Projeto Beta', 'Carlos Lima', 'Recursos Humanos')
('Projeto Gamma', 'Paula Souza', 'Financeiro')

Conexão encerrada.
```

## 🖼️ Diagrama Entidade-Relacionamento

Abaixo está o diagrama conceitual das tabelas e seus relacionamentos:

![Diagrama ER](diagrama_er_empresa%20(1).png)
