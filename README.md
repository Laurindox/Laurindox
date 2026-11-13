## Adlem Laurindo

**AI Engineer | Automation Engineer | AI Agents · Generative AI · LLM · MCP · APIs · CRM | Remote**

[LinkedIn](https://linkedin.com/in/adlem-laurindox) · Versão em português no final da página.

### English

I'm an AI Engineer who builds LLM agents and the automations around them, with tool calling, guardrails and evaluation. I own the agent, the tools it calls (ERP, CRM, calendar, MCP) and the tests that decide when a version ships.

#### What I have built

- A customer support agent for an e-commerce store, put into production with a pause switch and failure alerts. It understands text, voice notes and photos, looks up the real order in the ERP, answers within fixed rules about what it may offer and hands sensitive cases to a person. A Redis buffer groups quick messages so it answers once, and it goes quiet when a human takes over.
- A secretary agent for clinics inside GoHighLevel, built and tested on a model clinic: it qualifies leads and books appointments through tools, with a daily reply cap and no stored conversations.
- Automations in n8n: a WhatsApp app for GoHighLevel (OAuth install, several sub-accounts, voice notes, connection watcher), payments that create the order in the ERP and post-sale messages triggered by the carrier's confirmed delivery.
- A permission layer for a Google Workspace MCP server: reads are free, writes need confirmation, permanent delete and forward are blocked.
- A multi-agent system for market research and copywriting, in progress: stages with defined inputs and outputs, and a person approves each stage and every spend.

#### How I work

I have been studying and building with AI and automation since 2024. I write the spec, build with Claude Code and test before I ship: every version is scored on new conversations written by an agent that never saw the prompt, and I retire a set once I tune against it. Two lessons stuck: a test written from the same source as the prompt measures nothing, and the bugs that matter only show up live, so I run both. My setup has skills, hooks that block risky actions and subagents chosen by task and cost.

**Courses:** Anthropic (Claude API, Model Context Protocol, Agent Skills, Subagents, Claude Code, Amazon Bedrock, Google Vertex AI) and OpenAI Academy.

**Specialties:** AI agents, conversational AI, generative AI, tool calling, orchestration, LLM evaluation, guardrails, monitoring, prompt engineering, context engineering, process automation, MCP, n8n, Claude, Gemini, OpenAI, APIs, CRM and ERP integration, WhatsApp, PostgreSQL, Supabase, Redis.

#### About the repositories

The production systems run inside client operations and carry credentials, order data and real customer conversations, so those repositories stay private. I walk through the architecture and decisions on a call, with screen share.

Open to remote AI Engineer roles, full-time or contract. Message me on [LinkedIn](https://linkedin.com/in/adlem-laurindox).

<details>
<summary><b>Português</b></summary>

Sou engenheiro de IA (AI Engineer) e construo agentes com LLM e as automações em volta deles, com tool calling, guardrails e avaliação. Cuido do agente, das ferramentas que ele chama (ERP, CRM, agenda, MCP) e dos testes que liberam cada versão.

#### O que eu já construí

- Um agente de atendimento para um e-commerce, em produção com chave de pausa e alertas de falha. Entende texto, áudio e foto, consulta o pedido real no ERP, responde dentro de regras fixas sobre o que pode oferecer e passa os casos sensíveis para uma pessoa. Um buffer no Redis junta as mensagens seguidas para ele responder uma vez só, e ele fica em silêncio quando um humano assume.
- Uma secretária de IA para clínicas dentro do GoHighLevel, testada em uma clínica-modelo: qualifica leads e marca consultas por ferramentas, com teto diário de respostas e sem guardar conversas.
- Automações em n8n: um app de WhatsApp para o GoHighLevel (instalação por OAuth, várias subcontas, áudio, vigia de conexão), pagamento que cria o pedido no ERP e mensagem de pós-venda disparada pela entrega confirmada pela transportadora.
- Uma camada de permissão para um servidor MCP do Google Workspace: leitura livre, escrita só com confirmação, apagar de vez e encaminhar bloqueados.
- Um sistema multiagente de pesquisa de mercado e copy, em construção: etapas com entradas e saídas definidas, e uma pessoa aprova cada etapa e cada gasto.

#### Como eu trabalho

Estudo e construo com IA e automação desde 2024. Escrevo a especificação, construo com o Claude Code e testo antes de entregar: cada versão é pontuada em conversas novas, escritas por um agente que nunca viu o prompt, e descarto o conjunto quando ajusto contra ele. Duas lições ficaram: teste escrito da mesma fonte do prompt não mede nada, e os bugs que importam só aparecem ao vivo, então faço os dois. Meu setup tem skills, hooks que bloqueiam ações de risco e subagentes escolhidos por tarefa e custo.

**Cursos:** Anthropic (Claude API, Model Context Protocol, Agent Skills, Subagents, Claude Code, Bedrock, Vertex AI) e OpenAI Academy.

**Especialidades:** agentes de IA, IA conversacional, IA generativa, tool calling, orquestração, avaliação de LLMs, guardrails, monitoramento, engenharia de prompt, engenharia de contexto, automação de processos, MCP, n8n, Claude, Gemini, OpenAI, APIs, integração de CRM e ERP, WhatsApp, PostgreSQL, Supabase, Redis.

#### Sobre os repositórios

Os sistemas em produção rodam dentro da operação de clientes e carregam credencial, dado de pedido e conversa real de consumidor, por isso esses repositórios ficam privados. Mostro a arquitetura e as decisões em chamada, com a tela compartilhada.

Aberto a vagas remotas de Engenheiro de IA, em tempo integral ou contrato. Me chame no [LinkedIn](https://linkedin.com/in/adlem-laurindox).

</details>
