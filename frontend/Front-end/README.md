# 🧩 Projeto Integrador — Desenvolvimento de Sistemas Orientado a Objetos (PI-ADS)

## 🎯 Objetivo
Desenvolver um sistema de **gestão acadêmica** com modelagem orientada a objetos, banco de dados relacional e prototipação de interfaces.

---

## 🧱 Tecnologias Utilizadas

| Camada | Tecnologia |
|--------|-------------|
| Linguagem | Java 23 |
| Framework | Maven |
| Banco de Dados | MySQL 8 |
| ORM / DAO | JDBC |
| IDE | IntelliJ IDEA / VS Code |
| Prototipação | Figma |
| Estilo Visual | Bootstrap 5 + CSS3 |

---

## 🧩 Estrutura do Projeto

src/
├── main/java/br/com/pi_ads/
│ ├── model/ # Classes de modelo (POJOs)
│ ├── dao/ # Camada de acesso a dados (DAO)
│ ├── util/ # Conexão JDBC (ConnectionFactory)
│ └── Main.java # Classe principal de teste
│
├── resources/frontend/
│ ├── index.html
│ ├── pessoa_fisica.html
│ ├── pessoa_juridica.html
│ ├── professor.html
│ ├── aluno.html
│ ├── fornecedor.html
│ └── style.css
│
└── database/pi_ads.sql

yaml
Copiar código

---

## 🗄️ Banco de Dados

- Banco: **pi_ads**
- Script completo: [`database/pi_ads.sql`](database/pi_ads.sql)
- Tabelas: `pessoa`, `pessoa_fisica`, `pessoa_juridica`, `aluno`, `professor`, `curso`, `fornecedor`, `matricula`, `endereco`

---

## 🧠 Diagramas UML

- Diagrama de **Casos de Uso**: mostra os cadastros principais
- Diagrama de **Classes**:
  - Pessoa (abstract)
    - PessoaFisica → Aluno / Professor
    - PessoaJuridica → Fornecedor
  - Curso / Matricula

*(inserir imagem do diagrama aqui quando disponível)*

---

## 🎨 Protótipos de Interface (Figma)

As telas do sistema foram modeladas no Figma:

👉 [**Acessar protótipo Figma**](#)  
*(link será adicionado após finalização das telas)*

Telas implementadas:
- Menu Principal  
- Cadastro de Pessoa Física  
- Cadastro de Pessoa Jurídica  
- Cadastro de Professor  
- Cadastro de Aluno  
- Cadastro de Fornecedor  

---

## 👥 Equipe

| Integrante | Função |
|-------------|---------|
| Airon Valentim | Desenvolvedor Full Stack |
| [Nome 2] | Modelagem e Banco de Dados |
| [Nome 3] | Prototipação (Figma) |
| [Nome 4] | Documentação e GitHub |

---

## 🚀 Execução do Projeto

1. **Importe o projeto no IntelliJ IDEA**
2. **Crie o banco no MySQL Workbench:**
   ```sql
   source database/pi_ads.sql;
Execute a classe Main.java

Abra index.html para visualizar o front-end

Suba o projeto no GitHub

📜 Licença
Projeto acadêmico desenvolvido no Senac — uso educacional e não comercial.