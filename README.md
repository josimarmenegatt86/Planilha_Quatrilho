# 🎴 Sistema de Gestão de Torneios de Quatrilho

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-green)
![Tech](https://img.shields.io/badge/Tech-Excel%20Avan%C3%A7ado-blue)
![Logic](https://img.shields.io/badge/Focus-L%C3%B3gica%20de%20Dados-orange)

Este projeto consiste numa ferramenta avançada de gestão e classificação para torneios regionais de **Quatrilho**. O sistema foi desenvolvido para automatizar a contagem de pontos, critérios de desempate e a geração de rankings anuais de forma precisa e escalável, resolvendo um problema real de organização desportiva através da tecnologia.

---

## 🚀 Funcionalidades e Tecnologias

O projeto utiliza recursos avançados de manipulação de dados para garantir a integridade das informações dos competidores:

* **Cálculo Automático de Ranking:** Utilização de fórmulas complexas como `RANK` e `SUMIF` para consolidar a pontuação de múltiplos torneios de forma dinâmica.
* **Critérios de Desempate Personalizados:** Lógica implementada para aplicar regras específicas da modalidade (como maior número de vitórias ou confronto direto) em caso de igualdade na pontuação total.
* **Validação de Dados por Região:** Segmentação de jogadores por cidade e clube, permitindo extrair estatísticas de participação e desempenho regional.
* **Interface Visual (UX):** Uso de **Formatação Condicional** para destacar os líderes do ranking e criar alertas visuais que facilitam a leitura rápida dos resultados.

---

## 📂 Estrutura e Arquitetura do Projeto

O sistema foi desenhado seguindo a lógica de camadas de um software, organizado nos seguintes pilares:

| Camada | Função Técnica | Componente do Arquivo |
| :--- | :--- | :--- |
| **Ingestão** | Cadastro centralizado de atletas e origem | Cadastro de Atletas |
| **Processamento** | Tabela dinâmica que processa resultados individuais | Matriz de Pontuação |
| **Cronograma** | Registo cronológico dos eventos do ano | Calendário de Torneios |
| **Interface (UI)** | Painel final com a classificação oficial atualizada | Ranking Geral |

---

## 🧠 Diferenciais Técnicos e Aplicação

Este projeto demonstra competências fundamentais para o desenvolvimento de sistemas:

1.  **Lógica de Programação:** Estruturação de condições complexas "se-então" para aplicar o regulamento do torneio sem intervenção manual.
2.  **Análise de Dados:** Limpeza, organização e consolidação de informações vindas de diferentes etapas e cidades.
3.  **Gestão de Projetos:** Entrega de uma solução funcional que atende a uma comunidade real, focando em escalabilidade e precisão.

---

## 🚀 Roadmap de Evolução (Próximos Passos)

Como parte do meu percurso de aprendizagem em **Python** e desenvolvimento de sistemas, este projeto está em constante evolução:

- [x] Estruturação da base de dados e automação de fórmulas no Excel.
- [x] Implementação de interface visual para consulta rápida.
- [ ] Migração da lógica de processamento para **Python (Pandas)**.
- [ ] Desenvolvimento de um Dashboard interativo via **Streamlit** para visualização web.

---

## 🧑‍💻 Autor
Desenvolvido por **Josimar Menegatt** * Professor e Programador *

---
"""
