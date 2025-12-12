# ⚖️ Dashboard de Análise de Ordens de Serviço

## 📋 Sobre o Projeto

Este projeto consiste em um Dashboard de Business Intelligence desenvolvido no **Power BI** para o monitoramento e gestão de Ordens de Serviço (OS) relacionadas a provimentos judiciais.
O objetivo principal é garantir o cumprimento dos prazos legais (SLA), permitindo que a equipe jurídica e operacional visualize rapidamente o volume de demandas, os prazos críticos e o status de cada solicitação.

## 🚀 Problema de Negócio
Neste contexto o não cumprimento de prazos (24h, 48h, 72h) pode acarretar complicações legais para a empresa. O desafio era sair de um controle manual/planilhas para uma visão centralizada que respondesse:
* Quantas ordens estão em aberto?
* Qual o percentual de cumprimento do SLA (Dentro vs. Fora do Prazo)?
* Quais equipamentos/serviços têm maior demanda judicial?

## 📊 Funcionalidades e KPIs
O painel foi estruturado para responder a perguntas-chave com as seguintes métricas:

* **Quantitativo Geral:** Visão totalizadora do volume de OS.
* **Gestão de Backlog:** Contagem de OS em Aberto para ação imediata.
* **Análise de SLA:** Segmentação visual entre *Concluído*, *Dentro do Prazo* e *Fora do Prazo*.
* **Análise por Categoria (Equipamento):** Gráfico de barras identificando os tipos de solicitações mais frequentes (ex: Judicial até 24h, 48h, etc.).
* **Painel Detalhado:** Tabela granular para consulta de número da OS, beneficiário, datas e solução aplicada.

## 🛠️ Tecnologias Utilizadas

* **Power BI Desktop:** Ferramenta principal de visualização e ETL.
* **Power Query:** Tratamento de dados, limpeza de colunas e tipagem.
* **DAX (Data Analysis Expressions):** Criação de medidas calculadas para contagens distintas e lógica de SLA.
* **Figma/PowerPoint:** Criação do background e layout para uma interface limpa e intuitiva.

## Visualização

<img width="1395" height="786" alt="image" src="https://github.com/user-attachments/assets/cd4b462b-b51f-447f-a15f-0ec05880f5f7" />

## 🔒 Proteção de Dados e Confidencialidade

Este dashboard foi desenvolvido utilizando **dados reais** de uma operação corporativa. 

Entretanto, em conformidade com a **LGPD (Lei Geral de Proteção de Dados)** e políticas de confidencialidade da empresa, a base de dados original **não foi disponibilizada** neste repositório. Todas as informações sensíveis (como nomes de beneficiários e identificadores específicos) exibidas nas imagens do portfólio foram anonimizadas ou ocultadas para preservar a privacidade das partes envolvidas.

## 🧠 Aprendizados

Durante o desenvolvimento deste projeto, foquei em:
1.  **Hierarquia Visual:** Destacar os "Big Numbers" no topo para leitura rápida.
2.  **Tratamento de Dados Sensíveis:** Garantir que a estrutura do relatório suporte a análise sem expor dados pessoais.
3.  **Usabilidade:** Inclusão de filtros de período e status para facilitar a navegação do usuário final.
