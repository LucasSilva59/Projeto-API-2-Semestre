# 📌 MVP - Prevlog

## 🎯 Objetivo do MVP
> Prover ao IPEM-SP um painel de visualização no dashboard com dados filtrados e tratados em Python sobre acidentes envolvendo cargas perigosas nas rodovias de São Paulo, permitindo a identificação das classes de risco e das vias com maior incidência.  

---

## 📝 Descrição da Solução
> Esta primeira etapa visa a transformação de dados brutos de acidentes com cargas perigosas em São Paulo em inteligência visual para o IPEM-SP. Funcionalmente, usaremos Python no Google Colab para limpar, normalizar e analisar o dataset, culminando na entrega de um Dashboard Inicial de visualizações que identificam classes de risco e rodovias críticas, tudo versionado no GitHub. A limitação conhecida é que o dataset de origem possui falhas e inconsistências (dados quebrados), e a entrega não inclui interface web ou integração de sistemas. O escopo é reduzido à prova de conceito analítica, focando apenas na rápida geração de valor para o planejamento de fiscalização.

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
| 1 | Como cliente, quero um dashboard inicial para visualização do tipo de produto, situação cadastral e etc.         | Alta       |  8 Dias   |
| 2 | 	Como cliente, quero os dados limpos e normalizados no Google Colab.         | Alta      | 10 Dias   |
| 3 | Como cliente, quero versionar todo o código e dados no GitHub.         | Média      | 6 Dias   |

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                          | Status   |
|--------|----------------------------------------------|----------|
| 01     | Dashboard inicial de visualização (tipo de produto); Dados limpos no Google Colab; Versionamento no GitHub.                        | Concluído|
| 02     | Visualização de acidentes com caminhões; Inclusão do período 2018-2023; Análise de produtos perigosos do RAPP; Conversão e padronização de unidades de medida (kg e L).                           | Em andamento |
| 03     | Mapeamento de pontos críticos (próximos a áreas de descanso); Análise de origem/destino e jurisdição rodoviária; Dashboard final intuitivo; Documentação técnica e Apresentação final.                           | Em andamento |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualizar o Dashboard Inicial contendo os principais indicadores de tipo de produto e situação cadastral para a análise preliminar dos dados.  
- O sistema deve registrar o código de limpeza no Google Colab deve ser capaz de gerar e o GitHub deve conter o arquivo de dados limpos e normalizados, pronto para uso posterior.  
- Métricas coletadas: Taxa de Integridade, percentual de registros válidos mantidos após o processo de limpeza e normalização dos dados. Disponibilidade do Código, confirmação de que todo o código e os dados estão versionados no repositório GitHub, acessíveis e funcionais.  

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP

 5 (Total de membros da equipe de desenvolvimento que validaram a funcionalidade).  
- Feedback qualitativo (positivo/negativo) 

100% Positivo. A equipe concordou que o MVP atende às Histórias de Usuário da Sprint 1 (Dashboard, Dados Limpos, Versionamento) e que a solução é tecnicamente viável.
- Indicadores de negócio  

**Eficiência na Pré-Análise:** Redução do tempo necessário para iniciar a análise estratégica dos dados de acidentes, uma vez que o dataset já está limpo, normalizado e com visualizações prontas.

**Prontidão da Base de Dados:** Criação de uma base de dados sólida e versionada (GitHub), garantindo a continuidade do projeto nas próximas sprints sem retrabalho na limpeza inicial.

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback

Refinamento da Filtragem: Otimizar e refatorar os scripts de Python para garantir uma filtragem de dados mais precisa e robusta. Esta melhoria visa resolver as inconsistências encontradas na Sprint 1, impactando diretamente a qualidade do dashboard.

- Ajustes de usabilidade  

Clareza do Dashboard: Fazer ajustes visuais no Dashboard Inicial para que a representação do "tipo de produto" e "situação cadastral" seja imediatamente intuitiva e clara para o Fiscal do IPEM-SP.

- Expansão de funcionalidades para próximo incremento  

**Expansão da Análise Temporal e Veicular:** Incluir os dados dos anos de 2018 a 2023 e focar na visualização de acidentes envolvendo caminhões.

**Análise Logística Profunda:** Implementar a lógica de conversão de unidades de medida (toneladas e m³ para kg e litros) e iniciar a análise dos produtos perigosos utilizando a base de dados do RAPP.

**Preparação para o Mapeamento:** Preparar o dataset para incluir variáveis de origem/destino e jurisdição rodoviária (municipal, estadual, federal), essenciais para o mapeamento da Sprint 3.

---

## 📂 Anexos / Evidências
![Demonstração do Script Python](https://github.com/user-attachments/assets/e2bd0a89-77c8-43a9-baf5-c69fe3ce36d7)
**[➡️ Clique aqui para acessar o código-fonte do script Python](https://colab.research.google.com/drive/1qR-ixf_FR2FrlbDQna8Yg0tBSB3W6wUf?usp=sharing
)**

<a href="https://app.powerbi.com/groups/me/reports/2b6b8923-e4ea-4d7a-bdb7-d0d25faae3bf?ctid=cf72e2bd-7a2b-4783-bdeb-39d57b07f76f&pbi_source=linkShare" target="_blank">
  <img src="https://github.com/user-attachments/assets/5323ee0b-ad62-4099-9c0d-dc172833e484" alt="Visão Geral do Dashboard Power BI" width="49%">
</a>

<a href="https://app.powerbi.com/groups/me/reports/2b6b8923-e4ea-4d7a-bdb7-d0d25faae3bf?ctid=cf72e2bd-7a2b-4783-bdeb-39d57b07f76f&pbi_source=linkShare" target="_blank">
  <img src="https://github.com/user-attachments/assets/da27a543-44ce-43ce-8997-d1ba761664db" alt="Detalhes do Dashboard Power BI" width="49%">
</a>
⬆️ Clique em uma das imagens para acessar o Power Bi.
