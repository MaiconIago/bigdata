# 📊 Relatório Técnico - Projeto Big Data com Python

Este projeto foi desenvolvido em ambiente acadêmico com foco na exploração, análise e visualização de grandes volumes de dados, aplicando técnicas de ciência de dados, aprendizado de máquina e inteligência artificial.

---

## 🎯 Objetivos

- **Coletar e tratar grandes volumes de dados:** a partir de fontes confiáveis, garantindo qualidade e consistência.
- **Analisar e visualizar informações relevantes:** por meio de análises estatísticas e representações gráficas.
- **Aplicar modelos de Machine Learning:** para prever comportamentos com base em dados históricos.
- **Treinar e testar modelos de IA no Databricks:** utilizando recursos escaláveis em nuvem.

---

## 🛠 Tecnologias Utilizadas

| Ferramenta         | Finalidade                                                                 |
|--------------------|---------------------------------------------------------------------------|
| **Python**         | Linguagem principal de programação e análise de dados                     |
| **Pandas**         | Manipulação e tratamento de dados                                         |
| **Matplotlib/Seaborn** | Criação de gráficos e visualizações estatísticas                     |
| **Databricks**     | Processamento em larga escala e execução de notebooks                     |
| **GitHub**         | Controle de versão e colaboração                                          |
| **Trello**         | Gestão de tarefas com metodologia Kanban                                  |

---

## 📌 Etapas do Projeto

1. **Definição da ideia:**
   - Tema e objetivos definidos com base na viabilidade técnica.
2. **Coleta e limpeza de dados:**
   - Remoção de duplicatas, tratamento de valores nulos e padronização.
3. **Análise exploratória e visualizações:**
   - Identificação de padrões, tendências e correlações.
4. **Modelagem preditiva:**
   - Aplicação de algoritmos de aprendizado de máquina, como XGBoost.
5. **Desenvolvimento de interface:**
   - Criação de dashboards interativos para visualização de insights.
6. **Publicação e apresentação:**
   - Documentação dos resultados, código no GitHub e apresentação acadêmica.

---

## 📈 Resultados Esperados

- **Visualizações Interativas:**
  - Dashboards dinâmicos com filtros e comparações visuais.
- **Site de Apresentação:**
  - Plataforma web com gráficos interativos e explicações sobre os modelos.

---

## 🧠 Relato Técnico

O modelo foi treinado para prever a gravidade de acidentes rodoviários com três classes:
- 0: Sem vítimas
- 1: Com vítimas feridas
- 2: Com vítimas fatais

**Algoritmo utilizado:** `XGBoost`, com balanceamento de classes via `SMOTE`.

**Variáveis consideradas:**
- Dia da semana, horário, rodovia, município
- Condições da via e do clima
- Número de veículos e pessoas envolvidas

**Resultados:**
- Boa performance para classe 1 (feridos): **Precisão: 0.79, Recall: 0.89**
- Baixa performance para classes 0 e 2
- **Acurácia global:** 72%

**Possíveis melhorias:**
- Uso de variáveis adicionais
- Ajustes de hiperparâmetros para melhorar sensibilidade nas classes minoritárias

---

## ✅ Conclusão

O projeto proporcionou uma experiência prática completa em ciência de dados, envolvendo desde a coleta e tratamento de dados até a visualização e modelagem preditiva.

Além das habilidades técnicas, os participantes desenvolveram competências como:
- Trabalho em equipe
- Organização e planejamento
- Autonomia na resolução de problemas

Este trabalho reforça o potencial transformador do Big Data em contextos acadêmicos, científicos e industriais.

---

## 📂 Estrutura Recomendada do Repositório

