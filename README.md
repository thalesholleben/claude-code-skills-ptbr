# Skills do Claude Code em português

Skills que eu uso todo dia no Claude Code e no Codex, escritas em português do Brasil por [Thales Gomes](https://thalesgomes.com). Este repositório é o índice: as cinco gratuitas têm repositório próprio e as pagas vivem na [loja de skills](https://thalesgomes.com/skills/).

Uma skill é uma pasta com um `SKILL.md` que ensina o agente a fazer uma tarefa do seu jeito, com as regras, os scripts e as referências que ele precisa. O agente só carrega a skill quando a tarefa pede, então ela não pesa no contexto o dia inteiro. Se você nunca criou uma, o guia [Skills do Claude Code: o que são, como criar e as melhores em português](https://thalesgomes.com/skills-do-claude-code) explica do zero.

## As gratuitas

Cinco skills de marketing, licença MIT, cada uma no seu repositório:

| Skill | O que faz |
|---|---|
| [copy-thief](https://github.com/thalesholleben/copy-thief) | Copy de página de vendas, advertorial e VSL para tráfego frio, com diagnóstico de consciência antes do texto |
| [google-ads-manager](https://github.com/thalesholleben/skill-google-ads) | Google Ads avançado: Smart Bidding, AI Max, palavra-chave, leilão, teste A/B e relatório |
| [linkedin-publisher](https://github.com/thalesholleben/linkedin-publisher) | Publica e apaga post no LinkedIn pela API oficial, com texto, imagem ou vídeo |
| [threads-publisher](https://github.com/thalesholleben/threads-publisher) | Publica, lista e apaga post no Threads pela API da Meta |
| [x-publisher](https://github.com/thalesholleben/x-publisher) | Publica, lê e apaga post no X pela API oficial |

### Como instalar

Clone o repositório da skill dentro da pasta de skills do agente. No Claude Code:

```bash
git clone https://github.com/thalesholleben/copy-thief ~/.claude/skills/copy-thief
```

No Codex a pasta é `~/.agents/skills/`. Depois é só pedir a tarefa em linguagem natural, o agente lê a descrição do `SKILL.md` e decide sozinho quando usar. Cada repositório tem o README com o que a skill precisa (chave de API, conta, ferramenta).

## As pagas

25 skills em 5 áreas, avulsas por R$ 57 ou R$ 97, ou todas juntas no [Pack de Skills](https://thalesgomes.com/skills/) por R$ 497, com 9 bônus que não são vendidos separados, 12 meses de atualização e garantia de 7 dias. Cada página explica a dor que a skill resolve, sem mapa técnico, porque o mapa é o produto.

### Pesquisa e estratégia

| Skill | O que faz | Avulsa |
|---|---|---|
| [deep-search-expert](https://thalesgomes.com/skills/deep-search-expert) | Pesquisa profunda com manifesto e evidência por afirmação, cruzando fonte oficial, fórum, GitHub e vídeo | R$ 97 |
| [seo-expert](https://thalesgomes.com/skills/seo-expert) | Ranquear no Google e ser citado por ChatGPT, Perplexity e AI Overviews, com intenção, E-E-A-T e dado estruturado | R$ 57 |
| [transcrever](https://thalesgomes.com/skills/transcrever) | Cola a URL do vídeo ou do áudio e sai a transcrição com resumo, por Whisper local ou pela API do Groq | R$ 57 |

### Design e frontend

| Skill | O que faz | Avulsa |
|---|---|---|
| [frontend-expert](https://thalesgomes.com/skills/frontend-expert) | Direção visual, tipografia, cor e composição com revisão anti-genérico, 300 arquivos de referência e fontes locais | R$ 97 |
| [animation-expert](https://thalesgomes.com/skills/animation-expert) | Animação web com CSS, WAAPI, GSAP, ScrollTrigger e SVG, com galeria executável e receita por intenção | R$ 57 |
| [logo-expert](https://thalesgomes.com/skills/logo-expert) | Logo do briefing ao kit: rotas de conceito, vetor com correção óptica, teste de redução, manual e favicon | R$ 97 |
| [page-speed-expert](https://thalesgomes.com/skills/page-speed-expert) | Core Web Vitals de verdade: LCP, INP, CLS, caminho crítico, imagem, fonte, script de terceiro e cache | R$ 57 |
| [web-builder-best-practices](https://thalesgomes.com/skills/web-builder-best-practices) | Site em PHP, HTML, CSS e JS sem framework pesado, da estrutura de pasta à publicação, com Core Web Vitals e segurança | R$ 57 |

### Marketing e tráfego

| Skill | O que faz | Avulsa |
|---|---|---|
| [meta-ads-expert](https://thalesgomes.com/skills/meta-ads-expert) | Meta Ads em 2026: Advantage+, Andromeda, público, criativo, teste, escala, com o imposto brasileiro já na conta | R$ 57 |
| [tracking-expert](https://thalesgomes.com/skills/tracking-expert) | Pixel, Tag Manager client e server-side, Conversions API, UTM e atribuição que batem com o que o cliente vê | R$ 57 |
| [instagram-organic-expert](https://thalesgomes.com/skills/instagram-organic-expert) | Instagram orgânico em 2026: formato, gancho, distribuição, busca, métrica e automação com IA sem tomar punição | R$ 57 |
| [social-design](https://thalesgomes.com/skills/social-design) | Arte PNG de post na medida de cada rede, com a sua marca e estratégia de gancho, prova, CTA e retenção de carrossel | R$ 97 |

### Software e infra

| Skill | O que faz | Avulsa |
|---|---|---|
| [api-expert](https://thalesgomes.com/skills/api-expert) | API REST em Express 5, NestJS 11 ou FastAPI com OWASP API Top 10, cache, fila, rate limit e observabilidade | R$ 57 |
| [security-checklist](https://thalesgomes.com/skills/security-checklist) | O checklist de pré-produção de SaaS: auth, autorização, upload, pagamento, webhook, headers, SSRF, supply chain e log | R$ 57 |
| [lgpd-baseline](https://thalesgomes.com/skills/lgpd-baseline) | LGPD para produto: base legal, dado sensível, retenção, direito do titular, DPA e plano de incidente | R$ 57 |
| [escala](https://thalesgomes.com/skills/escala) | Aguentar o pico: vertical contra horizontal, load balancer, Swarm ou k3s, stateless, fila, réplica de leitura e CDN | R$ 57 |
| [teste-de-carga](https://thalesgomes.com/skills/teste-de-carga) | k6 na prática: converter visita em RPS e VUs, escolher o teste certo, ler o joelho de capacidade e dimensionar a VPS | R$ 57 |
| [testes-automatizados-expert](https://thalesgomes.com/skills/testes-automatizados-expert) | Unitário, API, e2e, contrato, negativo, IDOR e BOLA, DAST e carga, rodando em infra efêmera | R$ 57 |
| [evolution](https://thalesgomes.com/skills/evolution) | WhatsApp pela Evolution API v2 e GO: instância, QR, webhook, mídia, grupo e as regras que evitam o ban | R$ 57 |
| [ci-cd-expert](https://thalesgomes.com/skills/ci-cd-expert) | Pipeline no GitHub Actions na medida do repo: CI, segurança, deploy com rollback e o que roda antes de cada merge | R$ 57 |
| [monitoring-expert](https://thalesgomes.com/skills/monitoring-expert) | Log, métrica, trace, uptime e alerta proporcionais ao risco do sistema, sem virar painel que ninguém olha | R$ 57 |

### Método e negócio

| Skill | O que faz | Avulsa |
|---|---|---|
| [cross-review](https://thalesgomes.com/skills/cross-review) | Claude Code e Codex revisando um ao outro, com veredito fechado, evidência e no máximo duas rodadas | R$ 97 |
| [enterprise-agentic-workflow](https://thalesgomes.com/skills/enterprise-agentic-workflow) | O projeto inteiro orquestrado: risco Q0, Q1 e Q2, executor Claude ou Codex por tarefa, gates, PR e checks | R$ 97 |
| [contador-expert](https://thalesgomes.com/skills/contador-expert) | MEI, ME, Simples, fator R, CNAE, pró-labore, NFS-e e ISS para quem vende software e serviço no Brasil | R$ 57 |
| [technology-contract-expert](https://thalesgomes.com/skills/technology-contract-expert) | Contrato de software, site, automação, agente e SaaS sob a lei brasileira, com as cláusulas que evitam a briga de escopo | R$ 57 |

## Outras skills em português

Se você mantém uma skill em português do Brasil, de sua autoria e com licença aberta, abra um pull request acrescentando a linha na tabela abaixo. Só entra skill de quem escreveu, com repositório público e README que explique o que ela faz.

| Skill | Autor | O que faz |
|---|---|---|
| | | |

## Guias relacionados

- [Claude Code em português: guia completo](https://thalesgomes.com/claude-code)
- [Skills do Claude Code: o que são, como criar e as melhores em português](https://thalesgomes.com/skills-do-claude-code)

## Licença

Este índice e as cinco skills gratuitas são MIT. As skills pagas têm licença de uso em projeto próprio e de cliente, sem revenda, descrita na loja.
