# Normalização e Modelagem Dimensional para Otimização de Dados

Este projeto apresenta a transformação de um modelo de dados relacional inicialmente não normalizado em uma estrutura otimizada para consultas analíticas. O processo envolve a normalização dos dados para eliminar redundâncias e a criação de um modelo dimensional, facilitando a análise eficiente e a geração de insights.

---

## 🚀 Objetivos

- Dividir uma tabela grande e redundante em tabelas normalizadas para melhor organização e integridade dos dados.
- Construir um modelo dimensional com tabelas de dimensões e fatos para otimizar consultas analíticas.

---

## 🛠️ Principais Atividades

- Criação de sete tabelas normalizadas (`cliente`, `carro`, `combustivel`, `locacao`, `diaria`, `entrega` e `vendedor`) utilizando chaves primárias e estrangeiras para garantir integridade referencial.
- Inserção dos dados nas tabelas usando comandos `INSERT INTO` e `SELECT DISTINCT` para evitar duplicidades.
- Desenvolvimento de três views dimensionais (`dim_carro`, `dim_cliente` e `dim_tempo`) e uma view de fatos (`fatos_vendas`) com uso de `JOINs` para conectar dimensões e fatos.
- Otimização do modelo para suportar consultas analíticas de forma rápida e eficiente.

---

## 🔧 Tecnologias e Ferramentas

- SQL (DDL e DML)
- Modelagem Relacional e Dimensional
- Ferramentas de banco de dados compatíveis com SQL

---

## ⚙️ Como Utilizar

1. Execute os scripts de criação das tabelas normalizadas.
2. Insira os dados nas tabelas correspondentes.
3. Crie as views dimensionais e de fatos.
4. Utilize as views para realizar consultas analíticas e relatórios.

---

## 🎯 Resultados e Benefícios

- Eliminação de redundâncias e melhoria na integridade dos dados.
- Estrutura de dados otimizada para análise, facilitando a criação de relatórios.
- Melhora significativa na performance das consultas analíticas.
- Modelo preparado para integração com ferramentas de BI e análise avançada.

---

## 📚 Aprendizados

Este projeto consolidou conhecimentos em normalização de dados, integridade referencial, modelagem dimensional e criação de views para análise. Além disso, aprimorou a habilidade em escrita e otimização de consultas SQL para contextos analíticos.

