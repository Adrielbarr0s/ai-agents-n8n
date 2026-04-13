## 📦 Estruturas Base e Laboratórios

Para facilitar a navegação, os fluxos de trabalho de estudo foram divididos por conceitos arquitetônicos:

### 🧠 Integrações com IA e Agentes
* **`Automacao_Estoque_Postgres_IA.json`**: **[NOVO]** Esteira autônoma de ponta a ponta. O sistema lê dados de estoque crítico em um banco **PostgreSQL**, utiliza a IA do **Google Gemini** para redigir e-mails personalizados de negociação para fornecedores, registra o log da operação no banco e dispara a mensagem automaticamente via **API do Gmail** (OAuth2).
* **`AIAgent.json`** / **`LLMAutomacao.json`**: Estruturas base de agentes conversacionais e automatizações de rotina integradas com LLMs.
* **`AnaliseSentimento.json`**: Processamento de Linguagem Natural (NLP) aplicado à classificação de textos e sentimentos.

### 🔄 Pipelines de Dados e ETL
* **`ETL.json`**: Fluxo completo de extração, transformação e carregamento (ETL) de dados estruturados.
* **`HTMLReport.json`**: Geração automatizada de relatórios visuais dinâmicos.
* **`APIRest.json`** / **`ConsultaBasica.json`**: Consumo, paginação e manipulação de payloads de APIs externas.

### 🔀 Roteamento e Manipulação de Dados (Data Wrangling)
* **`MergeFork.json`** / **`MergebyAppend.json`** / **`Mergebyindex.json`** / **`Mergebykey.json`**: Técnicas avançadas de junção de múltiplos arrays e composição de objetos JSON.
* **`Split.json`**: Separação de grandes volumes de dados em lotes (Batch processing) para evitar sobrecarga.
* **`If_switch.json`**: Roteamento condicional e lógicas avançadas de desvio de fluxo.

### ⚡ Gatilhos, Eventos e Resiliência
* **`Webhook.json`** / **`Form.json`**: Portas de entrada (endpoints) para coleta de dados externos em tempo real.
* **`Cron.json`** / **`Interval.json`**: Agendamento de rotinas e tarefas em segundo plano (CRON Jobs).
* **`Fallback.json`**: Estrutura de tratamento de erros e rotas alternativas, garantindo a resiliência e alta disponibilidade das automações.
* **`HumanLoop.json`**: Intervenção e aprovação humana no meio do processo automatizado (Human-in-the-loop).

### 🔐 Segurança e Atendimento
* **`BasicAuthentic.json`**: Laboratório de métodos de autenticação para consumo seguro de APIs protegidas.
* **`Chamados.json`** / **`ChamadosUrgentes.json`**: Estrutura de roteamento inteligente e triagem de tickets de suporte.
