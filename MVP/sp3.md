# 📌 MVP - Prevlog

## 🎯 Objetivo do MVP
> O objetivo principal deste MVP é estabelecer a inteligência geográfica e logística do projeto, transformando dados históricos de acidentes com cargas perigosas (2018-2023) em um Dashboard Analítico Básico funcional; a sprint visa aprimorar as Sprints anteriores e avaliar as principais rotas de cargas perigosas.

---

## 📝 Descrição da Solução
> A solução entregue nesta etapa é um Dashboard de Business Intelligence (BI) para o estado de São Paulo, construído sobre o modelo de dados refinado na Sprint 2; Foi acrescentado as princispais rotas das cargas perigosas com base em pesquisas da equipe.

---

## 👥 Personas / Usuários-Alvo
- **Persona 1: IPEM-SP**
    * **Descrição:** Órgão fiscalizador que busca prevenir acidentes com cargas perigosas no estado de São Paulo.
    * **Necessidades:** Acesso a dados centralizados sobre acidentes para otimizar a fiscalização e criar políticas de prevenção mais eficazes.
    * **Dores Atendidas:** O projeto transforma dados dispersos em inteligência, permitindo uma fiscalização proativa e direcionando recursos para áreas de maior risco.  
- **Persona 2: Fatec SJC. Prof. Jessen Vidal**
    * **Descrição:** Instituição de ensino superior focada na aplicação prática do conhecimento para resolver problemas reais do mercado.
    * **Necessidades:** Projetos reais em parceria com o mercado para que os alunos possam aplicar a teoria e ganhar experiência relevante.
    * **Dores Atendidas:** O projeto conecta a sala de aula a um desafio real, fornece uma base de dados complexa para análise e motiva os alunos com um trabalho de impacto social.

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
| 13 | Como cliente, quero uma tabela das principais oriegens e destino. | Alta | 2 Dias |
| 14 | Como cliente, quero uma tabela das principais rodovias em que transitam cargas perigosas. | Alta | 1 Dia |
| 15 | Como cliente, quero saber as principais rotas | Alta | Sprint 3 | 2 Dias |
| 16 | Como cliente, quero pagínas separadas para o dashboard de origem, destino e o dashboard de rotas. | Alta| 1 Dia |


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Dashboard inicial de visualização (tipo de produto, situação cadastral); Dados limpos no Google Colab; Versionamento no GitHub.                        | Concluído|
| 02     | Visualização de acidentes com caminhões; Inclusão do período 2018-2023; Análise de produtos perigosos do RAPP; Conversão e padronização de unidades de medida (kg e L).                           | Concluído |
| 03     | Análise de origem/destino e jurisdição rodoviária; Dashboard final intuitivo; Documentação técnica e Apresentação final.                          | Em andamento |

---

## 📊 Critérios de Aceitação
* **O MVP deve permitir que o usuário**
    * O MVP deve permitir que o usuário **visualize os 10 principais pares Origem-Destino (OD) com maior risco de acidentes** e **identifique os *hotspots*** no mapa de São Paulo.
* **O sistema deve registrar**
    * O sistema deve registrar **a conversão bem-sucedida de 100% dos registros de toneladas e m³ para quilogramas e litros**, garantindo a normalização das unidades de medida.
* **Métricas coletadas:**
    * **Taxa de acidentes por jurisdição:** Municipal, Estadual e Federal.
    * **Distribuição de acidentes por tipo de carga:** (Perigosa vs. Não Perigosa, conforme RAPP).
---

## 📈 Métricas de Validação
* **Número de usuários que testaram o MVP**
    * 5 (Total de membros da equipe de desenvolvimento que validaram a funcionalidade) + Orientador(es) e/ou representante do IPEM.

* **Feedback qualitativo (positivo/negativo)**
    * 100% Positivo. A equipe concorda que o MVP atende às Histórias de Usuário da Sprint 2, especialmente na visualização dos Hotspots e na correta apresentação dos fluxos na Matriz OD.
      
* **Acurácia da Identificação de Risco:** O dashboard deve permitir que o usuário identifique os 5 principais pares Origem-Destino e as 5 principais rodovias com risco de acidente.
  
    * **Prontidão para Tomada de Decisão:** O dashboard deve estar em um estado funcional onde os dados (2018-2023) possam ser apresentados ao IPEM para iniciar a análise estratégica das zonas de risco.  
---

## 🚀 Próximos Passos
* **Melhorias planejadas após feedback:**
    * Integrar ajustes finos no modelo de dados ou nos filtros do dashboard baseados no *feedback qualitativo* sobre a usabilidade da Matriz OD.

* **Ajustes de usabilidade:**
    * Refinar a experiência do usuário (UX) do dashboard, garantindo que o layout seja intuitivo e que todas as interações e filtros carreguem rapidamente.

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
