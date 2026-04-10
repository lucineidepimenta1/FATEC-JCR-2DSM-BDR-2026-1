# Requisitos ABP – Banco de Dados Relacional

Esta pasta contém a descrição dos requisitos da disciplina de Banco de Dados Relacional, desenvolvidos no contexto da Aprendizagem Baseada em Projetos (ABP).

---

## Objetivo

Os requisitos têm como objetivo orientar o desenvolvimento do banco de dados do projeto, garantindo a aplicação prática dos conceitos estudados em aula.

---

## Estrutura dos Requisitos

Os requisitos estão organizados em três etapas evolutivas:

### BDR.01 – Fundamentos e Consultas Relacionais
- Criação do banco de dados  
- Manipulação de dados (INSERT, UPDATE, DELETE)  
- Consultas básicas (SELECT, WHERE, ORDER BY, LIMIT)  
- Funções de agregação (COUNT, SUM, AVG, GROUP BY, HAVING)  
- JOIN (INNER JOIN, LEFT JOIN)  

---

### BDR.02 – Subconsultas e Otimização
- Subqueries  
- Consultas analíticas  
- Índices e otimização  

---

### BDR.03 – Recursos Avançados
- Views  
- Stored Procedures  
- Triggers  
- Regras de negócio no banco  

---

## Entregas

Para cada requisito, o grupo deve entregar:

- Script SQL completo  
- Consultas implementadas  
- Dados consistentes com o projeto  
- Evidências de funcionamento  

---

## Boas Práticas

- Organizar o código SQL em arquivos separados  
- Utilizar comentários explicativos  
- Manter padrão de nomenclatura  
- Testar todos os scripts antes da entrega  

---

## ⚠️ Importante

- O desenvolvimento é incremental (um requisito depende do anterior)  
- O banco deve evoluir ao longo do semestre  
- Não será aceito código que não execute corretamente  

---

## Dica

Pensem no banco de dados como parte central do sistema.  
As decisões tomadas aqui impactam diretamente o funcionamento da aplicação.

## 🗓️ Cronograma de Sprints – Projeto ABP

As aulas abaixo serão dedicadas ao desenvolvimento incremental do projeto, seguindo a metodologia de Sprints.

| Data       | Sprint         | Sugestão de Foco                                                                 | Requisito | Entrega Esperada |
|------------|----------------|----------------------------------------------------------------------------------|------------|------------------|
| 10/04/2026 | Aula Inicial   | Apresentação do projeto ABP, explicação dos requisitos e cronograma             | -          | Nenhuma (aula de orientação) |
| 24/04/2026 | Sprint 1       | Modelagem inicial do banco (entidades, atributos, PK e FK)                      | BDR.01     | DER/MER + descrição das tabelas |
| 08/05/2026 | Sprint 2       | Criação das tabelas (CREATE TABLE) + constraints                                | BDR.01     | Script SQL (CREATE TABLE) |
| 15/05/2026 | Sprint 3       | Inserção de dados (INSERT) + consultas básicas (SELECT, WHERE)                  | BDR.01     | Script SQL (INSERT + SELECT) |
| 22/05/2026 | Sprint 4       | UPDATE, DELETE + ORDER BY e LIMIT                                               | BDR.01     | Script SQL (UPDATE, DELETE + consultas) |
| 29/05/2026 | Sprint 5       | Funções de agregação (COUNT, SUM, AVG) + GROUP BY + HAVING                      | BDR.01     | Consultas com agregações |
| 09/06/2026 | Sprint 6       | JOIN (INNER e LEFT) + relatórios com múltiplas tabelas                          | BDR.01     | Consultas com JOIN (2 e 3 tabelas) |
| 19/06/2026 | Sprint 7       | Subqueries + índices + introdução a Views/Procedures                            | BDR.02/03  | Subqueries + índices + (1 view ou 1 procedure simples) |

---

## Entrega Final (BDR.03)

Os conteúdos avançados deverão ser entregues como consolidação final do projeto:

- Views
- Stored Procedures
- Triggers
- Regras de negócio

📅 Data: definida pelo professor

---

## Objetivo das Sprints

Cada sprint tem como objetivo acompanhar a evolução do projeto, permitindo:

- Entregas parciais e incrementais  
- Correções ao longo do desenvolvimento  
- Aplicação prática dos conteúdos das aulas  
- Feedback contínuo do professor  

---

## ⚠️ Importante

- O desenvolvimento é incremental (um requisito depende do anterior)  
- Entregas fora do prazo podem impactar na avaliação  
- Scripts que não executam não serão considerados  

---

## 💡 Dica

Os conteúdos avançados (Views, Procedures e Triggers) fazem parte da entrega final do projeto.
