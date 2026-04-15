# Prompt para Lovable — Pitch Deck B2B allu.

---

Crie uma apresentação de slides interativa (pitch deck) para a empresa **allu.** usar em calls de vendas B2B de locação de notebooks e celulares. A apresentação deve funcionar como um app React com navegação entre slides via botões de seta ou teclado.

---

## Design e identidade visual

> Baseado fielmente no site oficial allugator.com. A marca allu. é **light-first**: fundo branco, verde como acento pontual, preto para estados ativos. Não usar roxo em nenhum elemento.

### Paleta de cores

| Token | Hex | Uso |
|---|---|---|
| Verde primário (allu green) | `#3DBE5C` | Botões CTA, links, ícones ativos, badges de desconto, barra de progresso |
| Preto / ativo | `#111111` | Pills selecionadas, título principal, logo, slides escuros |
| Fundo principal | `#FFFFFF` | Fundo da maioria dos slides |
| Fundo secundário | `#F5F5F5` | Cards, áreas de imagem, fundo de seções |
| Texto corpo | `#333333` | Parágrafos e descrições |
| Texto secundário | `#888888` | Labels, breadcrumbs, metadados |
| Bordas e divisores | `#E5E5E5` | Separadores, bordas de cards e pills não selecionadas |
| Branco | `#FFFFFF` | Texto sobre fundos escuros |

### Logo "allu."

- Renderizar como texto: `allu` em `#111111` peso 800 + ponto `.` em `#3DBE5C` peso 800
- Nunca usar caixa alta — sempre lowercase
- Ex: `<span style="color:#111111;font-weight:800">allu</span><span style="color:#3DBE5C;font-weight:800">.</span>`

### Tipografia

- **Fonte principal:** `Plus Jakarta Sans` (Google Fonts) — pesos 400, 600, 700, 800
- **Alternativa aceitável:** `DM Sans` ou `Nunito Sans`
- **Labels uppercase:** `font-size: 11px; font-weight: 600; letter-spacing: 0.08em; text-transform: uppercase; color: #888888`
- Títulos grandes: peso 800, cor `#111111`
- Subtítulos: peso 400–500, cor `#888888`

### Estilo geral

- **Fundo padrão:** branco `#FFFFFF` — a maioria dos slides é clara e clean
- **Slides de destaque** (capa, CAPEX→OPEX, CTA): fundo `#111111`, textos brancos, verde como único acento colorido
- **Verde usado com parcimônia:** apenas em CTAs, links, ícones-chave e badges — nunca como fundo de slide inteiro
- **Border-radius generoso:** `12px` cards, `9999px` pills e botões
- **Sombras sutis:** `box-shadow: 0 2px 12px rgba(0,0,0,0.07)` — nunca sombras pesadas
- **Sem gradientes** — design flat e limpo
- **Pills / estados selecionados:** fundo `#111111`, texto branco (igual às pills "24 meses" e "256GB" do site)
- **Pills não selecionadas:** fundo branco, borda `#E5E5E5`, texto `#333333`
- **Ícones:** lucide-react — verde `#3DBE5C` para destaques, `#888888` para secundários

### Botões

- **Primário (CTA):** fundo `#3DBE5C`, texto `#111111` peso 700, border-radius pill (`9999px`), padding `14px 32px` — idêntico ao botão "Assinar" do site
- **Secundário:** fundo branco, borda `1px solid #E5E5E5`, texto `#333333`

### Formato e navegação

- 16:9, tela cheia (`100vw × 100vh`), sem scroll vertical
- **Barra de progresso** fina no topo, cor `#3DBE5C`
- **Contador de slides** no rodapé centralizado: `"3 / 10"`, cor `#888888`, `font-size: 12px`
- **Botões de navegação:** chevron-left / chevron-right (lucide-react), cor `#111111`, discretos
- Suporte a teclas de seta do teclado
- Botão fullscreen discreto no canto superior direito (ícone `Maximize2` do lucide)

---

## Estrutura: 10 slides

---

### Slide 1 — Capa (fundo escuro `#111111`)

- Logo "allu." no topo esquerdo (versão clara: "allu" branco + ponto verde `#3DBE5C`)
- Centralize verticalmente:
  - Tag pill pequena: `LOCAÇÃO B2B` — fundo `rgba(61,190,92,0.15)`, texto `#3DBE5C`, border-radius pill
  - Título grande (h1, branco, peso 800): **"Tecnologia de ponta para o seu time, sem comprometer o caixa."**
  - Subtítulo (`#888888`): "Locação de notebooks e celulares para empresas — modelo as a service."
- Rodapé: site `alluempresas.com` em texto bem pequeno, `#888888`

---

### Slide 2 — Agenda da call (fundo branco `#FFFFFF`)

- Logo "allu." no topo esquerdo (versão escura padrão)
- Tag pill: `AGENDA` — estilo label uppercase verde
- Título (peso 800, `#111111`, grande à esquerda): **"Como vamos usar nosso tempo hoje"**
- Subtítulo (`#888888`): "Agenda aberta — você guia o ritmo."
- 4 cards horizontais lado a lado, cada um com número em pill verde `#3DBE5C`, ícone lucide e texto:
  1. **Entender seu contexto** — "Queremos conhecer os desafios da sua empresa antes de falar sobre nós."
  2. **Apresentar a allu.** — "Quem somos, o que fazemos e por que empresas escolhem a gente."
  3. **Explorar como podemos ajudar** — "Cases, modelo de locação e o que está incluso."
  4. **Definir próximos passos** — "Proposta customizada ou já fechar? Você decide."
- Cards com fundo `#F5F5F5`, borda `1px solid #E5E5E5`, border-radius 16px
- Número do card: pill `#111111` com texto branco (igual ao estado selecionado do site)

---

### Slide 3 — Investigação (fundo `#F5F5F5`)

- Logo "allu." no topo esquerdo
- Tag pill: `USO INTERNO` — fundo `#111111`, texto branco, border-radius pill (sinaliza que é guia do vendedor)
- Título (`#111111`, peso 800): **"Antes de falar sobre nós, queremos entender o seu cenário."**
- Subtítulo (`#888888`): "Perguntas que guiam nossa conversa"
- 6 cards em grid (2 colunas × 3 linhas), cada card com ícone lucide verde `#3DBE5C` e texto `#333333`:
  1. Laptop — "Quantos colaboradores usam notebooks ou celulares hoje?"
  2. Package — "Como funciona o ciclo de compra atual desses equipamentos?"
  3. AlertCircle — "Qual é a maior dor na gestão desse parque tecnológico?"
  4. TrendingUp — "Tem previsão de crescimento de time nos próximos 6 a 12 meses?"
  5. Clock — "Quanto tempo leva hoje para equipar um novo colaborador?"
  6. DollarSign — "Como está sendo tratado o custo de equipamentos hoje — CAPEX ou já existe algum OPEX?"
- Cards com fundo `#FFFFFF`, borda esquerda `3px solid #3DBE5C`, border-radius `12px`, sombra sutil
- Nota no rodapé em itálico, `font-size: 11px`, cor `#888888`: "Guia interno para o vendedor — não compartilhar a tela neste slide."

---

### Slide 4 — Quem é a allu. (fundo branco `#FFFFFF`)

- Logo "allu." no topo esquerdo
- Tag pill: `SOBRE A ALLU.` — label uppercase verde
- Título (`#111111`, peso 800): **"A maior empresa de assinatura de eletrônicos da América Latina."**
- Subtítulo (`#888888`): "Desde 2016 ajudando pessoas e empresas a ter tecnologia de ponta sem precisar comprar."
- 4 cards de métricas em linha, fundo `#F5F5F5`, border-radius `16px`:
  - Número grande em `#3DBE5C` peso 800 + label em `#888888` abaixo:
  - **+55.000** — clientes ativos
  - **+300** — contratos B2B ativos
  - **+8 anos** — no mercado
  - **R$ 329/mês** — por equipamento (a partir de)
- Linha divisória `#E5E5E5` abaixo dos cards
- Texto complementar (`#888888`): "Líderes em assinatura de iPhone no Brasil, agora com foco total em equipar empresas com o melhor da tecnologia."

---

### Slide 5 — Parceiros e Clientes (fundo branco `#FFFFFF`)

- Logo "allu." no topo esquerdo
- Tag pill: `ECOSSISTEMA` — label uppercase verde
- Título (`#111111`, peso 800): **"Empresas que confiam na allu."**
- Dividido em 2 seções lado a lado, separadas por linha divisória `#E5E5E5`:

**Seção esquerda — Parceiros estratégicos**
- Label uppercase `#888888`: `PARCEIROS`
- 4 badges com fundo `#F5F5F5`, borda `1px solid #E5E5E5`, border-radius `12px`, texto `#111111` peso 700:
  - **Acer** — "Fabricante oficial dos notebooks"
  - **PicPay** — "Fintech parceira"
  - **Flash** — "Benefícios corporativos"
  - **Livelo** — "Programa de pontos"

**Seção direita — Clientes que já locam**
- Label uppercase `#888888`: `CLIENTES`
- 4 badges mesma estética:
  - **Santos FC** — "Time de futebol"
  - **Internacional** — "Time de futebol"
  - **G4 Educação** — "Escola de negócios"
  - **The News** — "Empresa de mídia"

- Rodapé do slide (`#888888`, itálico): "E mais de 300 empresas de diferentes segmentos em todo o Brasil."

---

### Slide 6 — Como funciona (fundo escuro `#111111`)

- Logo "allu." no topo esquerdo (versão clara: "allu" branco + ponto verde)
- Tag pill: `O MODELO` — fundo `rgba(61,190,92,0.15)`, texto `#3DBE5C`
- Título (branco, peso 800): **"Simples como deveria ser."**
- Subtítulo (`#888888`): "Três etapas para equipar o seu time sem burocracia."

- 3 cards em linha conectados por seta `→` (cor `#3DBE5C`) entre eles:
  1. Ícone `Laptop` verde — **Escolha os equipamentos** — "Notebooks Acer ou iPhones — você decide o modelo e a quantidade."
  2. Ícone `FileText` verde — **Assine o contrato** — "Prazos de 12, 24, 36 ou 48 meses. A maioria prefere 24 ou 36."
  3. Ícone `CheckCircle` verde — **Receba e use** — "Entrega e suporte incluídos. Substituição em até 48h se precisar."

- Cards com fundo `rgba(255,255,255,0.05)`, borda `1px solid rgba(255,255,255,0.1)`, border-radius 16px
- Abaixo dos cards, 2 pills de destaque centralizados:
  - "A partir de **R$ 329/mês** por equipamento"
  - "Ticket médio: **R$ 3.300/mês**"
- Pills com fundo `#3DBE5C`, texto `#111111` peso 700, border-radius pill

---

### Slide 7 — O que está incluso (fundo branco `#FFFFFF`)

- Logo "allu." no topo esquerdo
- Tag pill: `TUDO INCLUSO` — label uppercase verde
- Título (`#111111`, peso 800): **"Uma assinatura. Zero dor de cabeça."**
- Subtítulo (`#888888`): "Tudo que sua empresa precisa para manter o parque tecnológico em ordem."
- Grid 2×3 de cards (6 benefícios), fundo `#F5F5F5`, borda `1px solid #E5E5E5`, border-radius `14px`:
  1. Ícone `Laptop` verde — **Equipamento novo** — "Notebooks Acer ou iPhones direto de fábrica, sem recondicionados."
  2. Ícone `Headphones` verde — **Suporte técnico** — "Atendimento humanizado com SLA de resolução em até 48 horas."
  3. Ícone `RefreshCw` verde — **Substituição garantida** — "Equipamento com problema? Mandamos um substituto em até 48h."
  4. Ícone `Shield` verde — **Seguro incluso** — "Cobertura para danos acidentais e roubo no contrato."
  5. Ícone `LayoutDashboard` verde — **Portal de gestão** — "Gerencie contratos e colaboradores em um painel centralizado."
  6. Ícone `TrendingUp` verde — **Escala com você** — "Aumentou o time? Adicionamos novos equipamentos sem burocracia."
- Ícones na cor `#3DBE5C`, título do card `#111111` peso 700, descrição `#888888`

---

### Slide 8 — CAPEX → OPEX (fundo escuro `#111111`)

- Logo "allu." no topo esquerdo (versão clara)
- Tag pill: `VANTAGEM FINANCEIRA` — fundo `rgba(61,190,92,0.15)`, texto `#3DBE5C`
- Título (branco, peso 800): **"Pare de imobilizar capital em equipamentos."**
- Subtítulo (`#888888`): "Transforme CAPEX em OPEX e libere caixa para o que realmente importa."

- Tabela comparativa com 3 colunas, fundo `rgba(255,255,255,0.04)`, border-radius `16px`:
  - Coluna 1 — critério (texto `#888888`)
  - Coluna 2 — "Compra (CAPEX)" — cabeçalho branco
  - Coluna 3 — "allu. Locação (OPEX)" — cabeçalho em pill `#3DBE5C`/`#111111`, destaque sutil de coluna

  | Critério | Compra (CAPEX) | allu. Locação (OPEX) |
  |---|---|---|
  | Investimento inicial | Alto (R$ 5k–10k/unidade) | Zero |
  | Previsibilidade de custo | Baixa | Alta — parcela fixa mensal |
  | Equipamento sempre atualizado | Não | Sim — upgrade no fim do contrato |
  | Suporte e manutenção | Custo adicional | Incluso |
  | Dedutível de impostos (IRPJ, CSLL, PIS, COFINS) | Parcialmente | 100% do valor da parcela |
  | Gestão de ativos | Manual / sem visibilidade | Portal centralizado |
  | Escalabilidade | Lenta e cara | Imediata |

  - Coluna CAPEX: ícone `X` cor `#EF4444` (vermelho) para cada item
  - Coluna allu.: ícone `Check` cor `#3DBE5C` para cada item
  - Linhas separadas por `border-top: 1px solid rgba(255,255,255,0.07)`
  - Cabeçalho da coluna allu. com pill verde `#3DBE5C`, texto `#111111`

---

### Slide 9 — Por que a allu. (fundo branco `#FFFFFF`)

- Logo "allu." no topo esquerdo
- Tag pill: `NOSSOS DIFERENCIAIS` — label uppercase verde
- Título (`#111111`, peso 800): **"O que nos torna diferentes de qualquer outra opção."**
- 4 cards grandes em grid 2×2, fundo `#F5F5F5`, borda `1px solid #E5E5E5`, border-radius `16px`:
  1. Ícone `Handshake` verde — **Parceria com a Acer** — "Acesso direto ao fabricante significa equipamentos premium, preços competitivos e condições exclusivas que nenhuma locadora comum consegue oferecer."
  2. Ícone `RefreshCcw` verde — **Economia circular** — "Após o contrato, os equipamentos são recuperados, reformados e realocados. Bom para o seu bolso e para o planeta."
  3. Ícone `MessageCircle` verde — **Atendimento humanizado** — "Nada de chatbot. Nossa equipe B2B acompanha você do onboarding ao fim do contrato, com conta dedicada."
  4. Ícone `Layers` verde — **Ecossistema completo** — "Notebook ou iPhone, do estagiário ao C-level — temos o equipamento certo para cada perfil de colaborador."
- Título do card `#111111` peso 700, descrição `#888888`
- Hover: `box-shadow: 0 4px 20px rgba(61,190,92,0.15)` — sombra verde sutil

---

### Slide 10 — Próximos Passos / CTA (fundo escuro `#111111`)

- Logo "allu." no topo esquerdo (versão clara: "allu" branco + ponto verde)
- Centralize verticalmente:
  - Tag pill: `PRÓXIMOS PASSOS` — fundo `rgba(61,190,92,0.15)`, texto `#3DBE5C`
  - Título (branco, peso 800, grande): **"Pronto para equipar seu time com o que há de melhor?"**
  - Subtítulo (`#888888`): "Vamos montar uma proposta customizada para a sua empresa."
  - 3 cards em linha com os próximos passos:
    1. Ícone `ClipboardList` verde — **Diagnóstico** — "Você nos conta o tamanho do time e os equipamentos necessários."
    2. Ícone `FileText` verde — **Proposta em 24h** — "Enviamos uma proposta detalhada com valor por unidade e total mensal."
    3. Ícone `CheckCircle` verde — **Assinatura e entrega** — "Contrato assinado, equipamentos entregues em até 5 dias úteis."
  - Cards com fundo `rgba(255,255,255,0.05)`, borda `1px solid rgba(255,255,255,0.1)`, border-radius `16px`, texto branco
  - Botão CTA grande, estilo igual ao "Assinar" do site — fundo `#3DBE5C`, texto `#111111` peso 700, border-radius pill, padding `16px 48px`, label: **"Solicitar proposta agora"**
  - Abaixo do botão, `font-size: 12px`, cor `#888888`: `alluempresas.com`

---

## Comportamento e UX

- Navegação por **setas do teclado** (← →) e **botões visuais** no rodapé (`ChevronLeft` / `ChevronRight` do lucide-react, cor `#888888`)
- **Barra de progresso** fina no topo da tela (`height: 3px`), cor `#3DBE5C`, avançando conforme os slides
- **Contador de slides** no rodapé centralizado: `"3 / 10"`, `font-size: 12px`, cor `#888888`
- **Transição suave** entre slides (fade ou slide horizontal) com ~300ms via framer-motion
- Todos os slides devem **ocupar 100vw × 100vh**, sem scroll vertical
- O conteúdo de cada slide deve **caber na tela** sem precisar rolar
- Botão **fullscreen** discreto no canto superior direito (`Maximize2` do lucide, cor `#888888`)
- **Responsivo para 1280x720** no mínimo (uso em chamadas de vídeo via compartilhamento de tela)

---

## Stack técnica sugerida

- React + TypeScript
- Tailwind CSS
- lucide-react (ícones)
- framer-motion (transições suaves entre slides)
- Fonte **Plus Jakarta Sans** via Google Fonts (pesos: 400, 600, 700, 800)

---

## Observações finais

- Não use imagens externas — use apenas ícones lucide e tipografia para montar o visual
- Cada slide deve ser um componente separado
- Mantenha o código limpo e organizado por slide
- O slide 3 (Investigação) tem uma nota interna para o vendedor — pode deixar num tom levemente diferente (ex: borda ou tag "Uso interno")
- A apresentação será usada em chamadas de vídeo (Google Meet, Zoom), então legibilidade em tela compartilhada é prioridade
