<h1 align="center">Olá, eu sou o Francinaldo 👋</h1>

<p align="center">
  Engenheiro full-stack focado em plataformas multi-tenant de logística e agronegócio.<br/>
  Atualmente liderando a migração de uma stack legada Hasura → NestJS-Query + V2 front-end em React.
</p>

---

### 🧰 Stack principal

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" />
</p>

---

### 🚀 Highlights

- 🔄 **Migração Hasura → NestJS-Query** em plataforma multi-tenant de logística agro: 100+ módulos GraphQL, 15+ tenants, banco isolado por cliente resolvido dinamicamente pelo hostname. Sem downtime, em coexistência com a stack legada via Apollo com dois clientes (V1/V2).
- ⚡ **Event Trigger System** genérico em PostgreSQL + RabbitMQ substituindo o Actions/Event Triggers do Hasura: trigger SQL → `event_log` → worker cron com `FOR UPDATE SKIP LOCKED` publica para exchanges downstream. Reduziu acoplamento e destravou a saída do Hasura.
- 🚛 **Integração com provedor externo de rastreamento logístico** migrada de 20 consumers per-tenant para arquitetura com data-source unificada. Inclui JWT rotativo por request para eliminar Unauthorized em pods longevos.
- 📄 **Document AI** (Google) + pipeline de NFe XML: extração automática, fila RabbitMQ, validação pós-processamento — reduziu digitação manual em cargas recorrentes.
- 🧮 **Engine de cálculo automático de ICMS sobre frete**: alíquotas por UF origem/destino, regime tributário e natureza da operação resolvidas no back-end — eliminou planilhas paralelas e divergência em auditoria fiscal.

---

### 💼 Aberto a

Freelance/consultoria em **NestJS, GraphQL multi-tenant, arquitetura event-driven (RabbitMQ), migração de backend legado e integrações GCP/Firebase**. Pra conversar: [LinkedIn](https://www.linkedin.com/in/francinaldojrdiniz/) ou email abaixo.

---

### 📈 Atividade & reviews (inclui contribuições privadas)

<p align="center">
  <img src="./metrics.svg" alt="Metrics" />
</p>

---

### 📊 GitHub Stats

<p align="center">
  <a href="https://github.com/francinaldojrdiniz">
    <img height="180" src="https://github-readme-stats.vercel.app/api?username=francinaldojrdiniz&show_icons=true&show=prs_merged,reviews&theme=tokyonight&hide_border=true" />
  </a>
  <a href="https://github.com/francinaldojrdiniz">
    <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=francinaldojrdiniz&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&hide=html,css" />
  </a>
</p>

---

### 📫 Contato

<p>
  <a href="https://www.linkedin.com/in/francinaldojrdiniz/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:francinaldojuniorxd@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
