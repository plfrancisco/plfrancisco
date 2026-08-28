# Pedro Lucas Francisco

Estudante de **Tecnologia em Sistemas Inteligentes** na FATEC Pompeia (3º semestre), com foco em IA, desenvolvimento de software e dados. Atualmente estagio no Laboratório de Solos da Fundação Shunji Nishimura. Antes de migrar pra tecnologia, passei alguns anos na indústria — foi lá que peguei gosto por entender como as coisas funcionam de verdade.

📌 **Aberto a oportunidades de estágio / vaga júnior** em desenvolvimento (Python/back-end) ou dados.

---

### Stack

Python · pandas · NumPy · LangChain · LangGraph · LightGBM · FastAPI · PostgreSQL · Docker

_As tecnologias específicas de cada projeto (React, TypeScript, Streamlit, etc.) estão descritas abaixo._

---

### Projetos em destaque

#### Síntegra Twin — digital twin com agentes de IA para previsão de demanda
`Projeto corporativo · código privado` — desenvolvido em colaboração com a **Síntegra** (Grupo Jacto).

- **O que faz:** orquestra agentes de IA que geram previsões de demanda a partir do histórico de vendas.
- **Stack:** LangGraph + LangChain com modelos Gemini, forecast em LightGBM, back-end FastAPI + Pydantic, ETL com pandas e SQLAlchemy sobre PostgreSQL, front-end React 19 (TanStack, Vite, Tailwind). Docker Compose.

#### [ZelaMapa](https://github.com/plfrancisco/ZelaMapa) — plataforma GovTech de zeladoria urbana &nbsp;·&nbsp; [demo](https://zela-mapa.vercel.app)
- **O que faz:** cidadãos reportam ocorrências no mapa; gestores despacham e equipes de campo acompanham as ordens de serviço em tempo real.
- **Meu papel:** projeto solo, full-stack.
- **Destaques técnicos:** atualização em tempo real via WebSockets, controle de acesso por papel (admin / motorista / cadastrador) e logs de auditoria.
- **Stack:** FastAPI + WebSockets, MySQL, React + TypeScript + Vite + Tailwind, banco via Docker.

#### [IoT Fish Farming Simulator](https://github.com/plfrancisco/iot-fish-farming-simulator) — simulador de dados de sensores para piscicultura
- **O que faz:** gera leituras realistas de tanques (temperatura, pH, oxigênio) e injeta "crises de oxigênio" para servir de base a análises posteriores.
- **Meu papel:** projeto solo.
- **Destaques técnicos:** modelagem estatística com NumPy (ciclo senoidal de temperatura + ruído correlacionado), inserção em lote com `executemany` e controle de transações (commit/rollback) contra PostgreSQL/Neon.
- **Stack:** Python · NumPy · psycopg2 · PostgreSQL.

#### [Hospital Data Analytics](https://github.com/plfrancisco/hospital-data-analytics) — painel interativo de dados hospitalares
- **O que faz:** dashboard que cobre 9 áreas de análise (volume de atendimentos, recursos, processos, geografia, perfil demográfico).
- **Meu papel:** projeto solo — análise e visualização.
- **Destaques técnicos:** instalação automática de dependências e execução com um comando (`streamlit run app_dashboard.py`); mapas com Folium.
- **Stack:** Python · pandas · Streamlit · Plotly · Folium.

---

### De onde eu vim

Comecei no chão de fábrica: na **Jacto**, trabalhei com metrologia e usinagem, onde aprendi na prática o que significa precisão. Depois fui pra **Abase**, em suporte técnico de redes, resolvendo problema sob pressão e enxergando sistema como um todo. Essa bagagem ainda influencia como eu penso software hoje — gosto de entender o problema real antes de sair escrevendo código.

---

### Contato

- LinkedIn: [pedro-lucas-francisco](https://www.linkedin.com/in/pedro-lucas-francisco)
- Email: f.pedrolucas.2002@gmail.com
- Pompeia / SP
