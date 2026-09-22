<h1 align="center">Francisco de Assis</h1>

<p align="center">
  <strong>Engenheiro de Dados em formação</strong> · Analista de Dados Sênior<br>
  Pipelines, modelagem dimensional e qualidade de dados
</p>

---

## 🔧 O que eu construo

Meu trabalho é com banco em produção, não com dataset de exemplo. O que passa pela minha mesa:

**Auditoria de camada de BI em PostgreSQL.**
Engenharia reversa de um banco de 16 GB, com 1.021 chaves estrangeiras, multi-empresa e exclusão lógica. Reconstruí as métricas de faturamento a partir das tabelas cruas e validei contra o sistema oficial, batendo no centavo. No caminho, 7 bugs nas views de BI, entre eles um `OR` no lugar de um `AND` que deixava falta e cancelamento entrarem no faturamento.

**Modelagem dimensional versionada como código.**
Um fato e cinco dimensões escritos em TMDL e Power Query M. Texto puro, lido em diff, revisado como qualquer outro código. Consulta ancorada na tabela e não na aba da planilha, porque aba muda de lugar e coluna é renumerada todo mês.

**Pipeline em Python com suíte de testes.**
Consolidação de cinco bases num modelo mensal e anual, com cache, caminho de dados externalizado em config e uma bateria de testes que roda antes de qualquer entrega. Código e dado em lugares separados.

**Orquestração agendada.**
Extração, agregação e disparo do relatório em horário fixo, sem ninguém apertar botão.

> Esses projetos nascem de trabalho sob contrato, com dado sensível, e não podem ir ao ar como estão. Estão sendo reescritos com dados sintéticos. A fila está em **Em construção**, no fim da página.

---

## 🧰 Stack

<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=amazondynamodb&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS%20RDS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/DAX%20%C2%B7%20Power%20Query-373277?style=for-the-badge">
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
</p>

**Onde eu sou forte:** SQL analítico, modelagem dimensional, qualidade e validação de dados, Power BI e DAX.
**O que estou construindo agora:** carga incremental, orquestração e transformação versionada (dbt).

---

## 📌 Repositórios

| Projeto | O que é |
|---|---|
| [**RFM_e-commerce**](https://github.com/FranciscoAssislsj/RFM_e-commerce) | Transformação de base transacional em indicadores por cliente: recência, frequência e valor monetário. Mudança de grão, de nota fiscal para cliente. |
| [**organizador-arquivos**](https://github.com/FranciscoAssislsj/organizador-arquivos) | Automação em Python com estrutura: lógica separada da entrada, dependências declaradas e script de teste. |

---

## 🚧 Em construção

O que entra aqui a partir de outubro de 2026, em ordem:

- [ ] **Orquestração agendada** · fluxo de extração, agregação e entrega de relatório em horário fixo, com dados fictícios.
- [ ] **Qualidade de dados em SQL** · estudo de caso com as armadilhas que eu encontrei na prática: dinheiro em `double precision`, `UNION` que dobra linha, `COALESCE(-1)` criando registro fantasma, view materializada contra tempo real.
- [ ] **Junção de duas fontes sem chave comum** · normalização, match por ordem de chegada e regra temporal, sobre base sintética.
- [ ] **Pipeline com suíte de testes** · o esqueleto de engenharia (config externa, cache, harness de testes) sobre dados de varejo gerados.

---

## 📫 Contato

<p align="center">
  <a href="https://www.linkedin.com/in/franciscoalsj/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
  <a href="https://iassisoficial.com.br">
    <img src="https://img.shields.io/badge/Portf%C3%B3lio-000000?style=for-the-badge&logo=vercel&logoColor=white">
  </a>
  <a href="mailto:franciscofut25@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white">
  </a>
</p>
