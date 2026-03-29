# 🎴 Quatrilho Tournament Manager

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-green)
![Tech](https://img.shields.io/badge/Tech-Excel%20Avan%C3%A7ado-blue)
![Logic](https://img.shields.io/badge/Focus-L%C3%B3gica%20de%20Dados-orange)

## 📋 Sobre o Projeto
Este projeto nasceu da necessidade de organizar e profissionalizar o **Ranking Regional de Quatrilho**. O sistema automatiza a gestão de atletas e a pontuação acumulada de diversas etapas, garantindo transparência e precisão nos resultados.

---

## 🛠️ Arquitetura da Solução

O sistema foi estruturado para atuar como um pequeno "Software em Planilha", dividido em:

| Camada | Função Técnica | Recurso Utilizado |
| :--- | :--- | :--- |
| **Ingestão** | Cadastro de atletas e clubes | Validação de Dados |
| **Processamento** | Cálculo de pontos e desempates | `SOMASE`, `PROCX`, `ORDEM` |
| **Interface (UI)** | Visualização do Ranking Geral | Formatação Condicional |
| **Análise** | Desempenho por cidade/região | Tabelas Dinâmicas |

## 🚀 Diferenciais Técnicos

### 1. Inteligência de Ranking
A lógica de classificação não considera apenas o valor bruto, mas lida com **critérios de desempate automáticos**, evitando a necessidade de intervenção manual após a inserção dos resultados.

### 2. Escalabilidade regional
O modelo foi desenhado para suportar o crescimento do número de jogadores e etapas, mantendo a performance das fórmulas e a integridade dos dados.

### 3. Roadmap de Evolução
- [x] Estruturação da base de dados no Excel.
- [x] Automação de fórmulas de ranking.
- [ ] Migração da lógica para **Python (Pandas)**.
- [ ] Criação de Dashboard interativo com **Streamlit**.

---

## 🧑‍💻 Autor
Desenvolvido por **Josimar Menegatt** * Professor e Programador *

---
