# 📌 MVP - Prevlog

## 🎯 Objetivo do MVP
> O objetivo principal deste MVP é estabelecer a inteligência geográfica e logística do projeto, transformando dados históricos de acidentes com cargas perigosas (2018-2023) em um Dashboard Analítico Básico funcional; a sprint visa validar a precisão da conversão de unidades de medida (para quilogramas e litros) e a capacidade de mapear a Geografia do Risco, apresentando visualmente os Hotspots e a Matriz Origem-Destino (OD) para o estado de São Paulo, o que permitirá ao IPEM direcionar a fiscalização de forma proativa para as rotas e tipos de carga mais vulneráveis.  
 
---

## 📝 Descrição da Solução
> A solução entregue nesta etapa é um Dashboard de Business Intelligence (BI) para o estado de São Paulo, construído sobre o modelo de dados refinado na Sprint 1; esta solução inclui as funcionalidades cruciais de tratamento de dados, garantindo a conversão de todas as unidades de medida (toneladas e m³) para quilogramas e litros, e a visualização analítica, que compreende o Mapeamento de Hotspots de acidentes com caminhões por jurisdição rodoviária e a Matriz de Origem-Destino (OD) para as cargas perigosas, utilizando a base RAPP como filtro; esta versão inicial do dashboard será intuitiva e conterá filtros de tempo (2018-2023), mas se limitará à análise descritiva no escopo geográfico de São Paulo, sendo as análises mais avançadas e a expansão nacional reservadas para sprints posteriores.    

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
| 4 | Como cliente, quero visualizar acidentes envolvendo caminhões.         | Alta       | 1 Dia   |
| 5 | Como cliente, quero os dados dos anos de 2018 há 2023.         | Alta      | 1 Dia   |
| 6 |Como cliente, quero vizualizar produtos perigosos na base de dados do RAPP.| Alta | 3 Dias |
| 7 | Como cliente, quero a lista dos produtos perigosos e não perigosos. | Alta | 3 Dias |
| 8 | Como cliente, quero que seja considerado apenas as unidades de medidas em kilogramas e litros | Alta | 1 Dia |
| 9 | Como cliente, quero que as unidades de medidas toneladas e m³ sejam convertidas em kilogramas e litros | Alta | 1 Dia |
| 10 | Como cliente, quero saber a origem e destino das cargas perigosas. | Alta | 1 Dia |
| 11 | Como cliente, quero saber se os acidentes ocorreram em rodovias municipais, estaduais ou federais. | Alta | 2 Dias |
| 12 | Como cliente, quero ter um dashboard intuitivo e visual. | Alta | 2 Dias |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Dashboard inicial de visualização (tipo de produto, situação cadastral); Dados limpos no Google Colab; Versionamento no GitHub.                        | Concluído|
| 02     | Visualização de acidentes com caminhões; Inclusão do período 2018-2023; Análise de produtos perigosos do RAPP; Conversão e padronização de unidades de medida (kg e L).                           | Em andamento |
| 03     | Mapeamento de pontos críticos (próximos a áreas de descanso); Análise de origem/destino e jurisdição rodoviária; Dashboard final intuitivo; Documentação técnica e Apresentação final.                          | Planejando |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário [ação principal]  
- O sistema deve registrar [evento importante]  
- Métricas coletadas: [exemplo: tempo de resposta, taxa de uso]  

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP  
- Feedback qualitativo (positivo/negativo)  
- Indicadores de negócio (exemplo: % de adesão, redução de custo, etc.)  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)  
