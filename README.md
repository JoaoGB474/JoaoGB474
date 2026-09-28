<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1f2937,100:58a6ff&height=180&animation=twinkling&section=header&text=Jo%C3%A3o%20Gabriel%20Kirchesch&fontSize=36&fontColor=e6edf3&fontAlignY=36&desc=Software%20Engineer%20%C2%B7%20Distributed%20Systems%20%C2%B7%20Platform&descSize=15&descAlignY=56&descColor=8b949e" width="100%" />

<a href="https://github.com/JoaoGB474"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=620&lines=Building+multi-tenant+platforms;Real-time+systems+on+the+edge;Creator+of+perfil.wtf+%26+Arkanis;simple+%3E+clever" /></a>

<a href="https://perfil.wtf"><img src="https://img.shields.io/badge/perfil.wtf-0d1117?style=flat-square&logo=cloudflare&logoColor=F38020" /></a>
<a href="mailto:joaobernardino474@gmail.com"><img src="https://img.shields.io/badge/email-0d1117?style=flat-square&logo=gmail&logoColor=EA4335" /></a>
<img src="https://img.shields.io/badge/Brasil-0d1117?style=flat-square&logo=googlemaps&logoColor=34A853" />

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

Engenheiro de software full stack. Projeto e opero produtos de ponta a ponta — modelagem de dados, APIs, infraestrutura na edge, serviços de longa duração e a interface que o usuário final vê.

Meu foco está em **sistemas multi-tenant**, **tempo real** e **arquiteturas que custam pouco para rodar e pouco para manter**. Prefiro poucas peças bem escolhidas a muitas peças da moda, e trato observabilidade, idempotência e consistência transacional como requisitos, não como extras.

```ts
const joao = {
  focus:      ["platform engineering", "real-time systems", "product"],
  languages:  ["TypeScript", "JavaScript", "SQL / SurrealQL"],
  runtime:    ["Node.js", "Cloudflare Workers", "Linux (VPS)"],
  data:       ["SurrealDB", "PostgreSQL"],
  principles: ["simple > clever", "idempotent by default", "own the whole stack"],
};
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## Trabalho em destaque

### <img src="https://media.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif" width="24"> Arkanis — plataforma de bots para Discord

Infraestrutura para criar, hospedar e operar múltiplos bots de Discord a partir de um único painel.

- **Runtime multi-tenant** — um pool de processos gerencia N bots de clientes diferentes; o estado desejado vive no banco e o runtime converge para ele (modelo declarativo, sem deploy por bot).
- **SurrealDB como fonte de verdade** — configuração, tenants e estado de execução no mesmo modelo, com consultas em tempo real para propagar mudanças.
- **Dashboard de gestão** — provisionamento, configuração e acompanhamento dos bots sem acesso à infraestrutura.

`TypeScript` · `Node.js` · `SurrealDB` · `Discord Gateway`

### <img src="https://media.giphy.com/media/iY8CRBdQXODJSCERIr/giphy.gif" width="24"> [perfil.wtf](https://perfil.wtf) — perfis personalizáveis em produção

Plataforma pública de perfis com links, música, presença do Discord em tempo real, feed de imagens, loja e painel administrativo.

- **Edge-first** — Next.js 15 servido por Cloudflare Workers (OpenNext), com roteamento por subdomínio e host no middleware.
- **Serviço de presença dedicado** — processo persistente conectado ao Gateway do Discord, mantendo snapshots de presença fora do ciclo request/response.
- **Importação idempotente** — ingestão de histórico em lotes com cursor persistente, retomável após falhas e reinícios.
- **Pagamentos consistentes** — webhooks do Mercado Pago validados por assinatura; pedidos e benefícios atualizados na mesma transação.
- **Storage próprio** — serviço autenticado de upload com limites por tipo de mídia.
- **Migração de dados** — transição de PostgreSQL para SurrealDB sem perda de registros existentes.

`Next.js` · `Cloudflare Workers` · `SurrealDB` · `OAuth2` · `Mercado Pago` · `Tailwind`

## Stack

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,nextjs,react,tailwind&theme=dark" /><br/>
  <img src="https://skillicons.dev/icons?i=cloudflare,postgres,linux,nginx,docker,git&theme=dark" />
</p>

## Atividade

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=JoaoGB474&show_icons=true&count_private=true&include_all_commits=true&hide_title=true&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e&icon_color=58a6ff" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JoaoGB474&layout=compact&hide_border=true&bg_color=0d1117&title_color=e6edf3&text_color=8b949e" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=JoaoGB474&bg_color=0d1117&color=8b949e&line=58a6ff&point=e6edf3&area=true&hide_border=true" width="100%" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/JoaoGB474/JoaoGB474/output/snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/JoaoGB474/JoaoGB474/output/snake.svg" width="100%" />
  </picture>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58a6ff,50:1f2937,100:0d1117&height=110&section=footer&animation=twinkling" width="100%" />
