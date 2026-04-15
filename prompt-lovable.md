# Prompt para Lovable — Pitch Deck B2B allu.

---

Crie uma apresentação de slides interativa (pitch deck) para a empresa **allu.** usar em calls de vendas B2B de locação de notebooks e celulares. A apresentação deve funcionar como um app React com navegação entre slides via botões de seta ou teclado.

---

## Design e identidade visual

- **Fonte:** Inter (Google Fonts)
- **Cor primária:** `#6B21D9` (roxo vibrante — cor da marca allu.)
- **Cor escura:** `#1A0A3B` (roxo muito escuro, para fundos dos slides de destaque)
- **Cor de acento:** `#A78BFA` (lilás claro)
- **Verde de confirmação:** `#10B981`
- **Fundo slides claros:** `#FFFFFF`
- **Fundo slides escuros:** `#1A0A3B`
- **Estilo geral:** minimalista, clean, moderno — sem exagero de elementos. Muito espaço em branco, tipografia forte, ícones simples (lucide-react). Sem gradientes pesados — se usar gradiente, apenas sutil no fundo.
- **Formato:** 16:9, tela cheia (fullscreen), sem barra de navegação do browser aparente
- **Logo da allu.:** renderizar como texto com a fonte Inter Black — "allu" em roxo escuro + ponto final em `#6B21D9`. Ex: `<span>allu</span><span style="color:#6B21D9">.</span>`
- **Navegação:** barra de progresso discreta no rodapé + botões de seta esquerda/direita + suporte a teclas de seta do teclado
- **Indicador de slide:** "3 / 10" centralizado no rodapé, pequeno e sutil

---

## Estrutura: 10 slides

---

### Slide 1 — Capa (fundo escuro `#1A0A3B`)

- Logo "allu." no topo esquerdo (pequeno)
- Centralize verticalmente:
  - Tag pill pequena: `LOCAÇÃO B2B` em roxo claro com fundo `#2D1058`
  - Título grande (h1, branco): **"Tecnologia de ponta para o seu time, sem comprometer o caixa."**
  - Subtítulo (cinza claro): "Locação de notebooks e celulares para empresas — modelo as a service."
- Rodapé: site `alluempresas.com` em texto bem pequeno, cinza

---

### Slide 2 — Agenda da call (fundo escuro `#1A0A3B`)

- Logo "allu." no topo esquerdo
- Título (branco, grande à esquerda): **"Como vamos usar nosso tempo hoje"**
- Subtítulo cinza claro: "Agenda aberta — você guia o ritmo."
- 4 cards horizontais lado a lado, cada um com número, ícone e texto:
  1. 🔍 **Entender seu contexto** — "Queremos conhecer os desafios da sua empresa antes de falar sobre nós."
  2. 🏢 **Apresentar a allu.** — "Quem somos, o que fazemos e por que empresas escolhem a gente."
  3. 💡 **Explorar como podemos ajudar** — "Cases, modelo de locação e o que está incluso."
  4. 🎯 **Definir próximos passos** — "Proposta customizada ou já fechar? Você decide."
- Cards com fundo `rgba(255,255,255,0.06)`, borda sutil, border-radius 16px

---

### Slide 3 — Investigação (fundo escuro `#1A0A3B`)

- Logo "allu." no topo esquerdo
- Tag pill: `DIAGNÓSTICO`
- Título: **"Antes de falar sobre nós, queremos entender o seu cenário."**
- Subtítulo cinza: "Perguntas que guiam nossa conversa"
- 6 perguntas em cards (2 colunas x 3 linhas), cada card com ícone lucide e texto:
  1. 💻 "Quantos colaboradores usam notebooks ou celulares hoje?"
  2. 📦 "Como funciona o ciclo de compra atual desses equipamentos?"
  3. 😣 "Qual é a maior dor na gestão desse parque tecnológico?"
  4. 📈 "Tem previsão de crescimento de time nos próximos 6 a 12 meses?"
  5. ⏱️ "Quanto tempo leva hoje para equipar um novo colaborador?"
  6. 💰 "Como está sendo tratado o custo de equipamentos hoje — CAPEX ou já existe algum OPEX?"
- Cards com fundo `rgba(255,255,255,0.05)`, borda esquerda de 3px na cor `#6B21D9`
- Nota no rodapé do slide em itálico, bem pequena: "Este slide é um guia interno para o vendedor — não precisa ser compartilhado com o lead."

---

### Slide 4 — Quem é a allu. (fundo branco)

- Logo "allu." no topo esquerdo (versão roxa)
- Tag pill roxa: `SOBRE A ALLU.`
- Título escuro: **"A maior empresa de assinatura de eletrônicos da América Latina."**
- Subtítulo cinza: "Desde 2016 ajudando pessoas e empresas a ter tecnologia de ponta sem precisar comprar."
- 4 cards de métricas em linha, cada um com número grande em roxo e label cinza:
  - **+55.000** clientes ativos
  - **+300** contratos B2B ativos
  - **+8 anos** no mercado
  - **R$ 329/mês** por equipamento (a partir de)
- Abaixo dos cards, uma linha divisória e texto: "Líderes em assinatura de iPhone no Brasil, agora com foco total em equipar empresas com o melhor da tecnologia."

---

### Slide 5 — Parceiros e Clientes (fundo branco)

- Logo "allu." no topo esquerdo (versão roxa)
- Tag pill roxa: `ECOSSISTEMA`
- Título escuro: **"Empresas que confiam na allu."**
- Dividido em 2 seções lado a lado com linha divisória vertical:

**Seção esquerda — Parceiros estratégicos** (título `PARCEIROS` em label pequena cinza)
- 4 badges brancos com sombra sutil, texto em negrito escuro, em grid 2x2:
  - **Acer** — "Fabricante oficial dos notebooks"
  - **PicPay** — "Fintech parceira"
  - **Flash** — "Benefícios corporativos"
  - **Livelo** — "Programa de pontos"

**Seção direita — Quem já loca com a gente** (título `CLIENTES` em label pequena cinza)
- 4 badges brancos com sombra sutil, em grid 2x2:
  - **Santos FC** — "Time de futebol"
  - **Internacional** — "Time de futebol"
  - **G4 Educação** — "Escola de negócios"
  - **The News** — "Empresa de mídia"

- Texto no rodapé do slide em cinza claro: "E mais de 300 empresas de diferentes segmentos em todo o Brasil."

---

### Slide 6 — Como funciona (fundo escuro `#1A0A3B`)

- Logo "allu." no topo esquerdo
- Tag pill: `O MODELO`
- Título branco: **"Simples como deveria ser."**
- Subtítulo cinza claro: "Três etapas para equipar o seu time sem burocracia."

- 3 cards em linha (step-by-step), conectados por seta → entre eles:
  1. **Escolha os equipamentos** — "Notebooks Acer ou iPhones — você decide o modelo e a quantidade." Ícone: laptop
  2. **Assine o contrato** — "Prazos de 12, 24, 36 ou 48 meses. A maioria dos nossos clientes prefere 24 ou 36." Ícone: file-text
  3. **Receba e use** — "Entrega, configuração e suporte incluídos. Substituição em até 48h se precisar." Ícone: check-circle

- Cards com fundo `rgba(255,255,255,0.08)`, borda sutil, border-radius 16px, ícone em roxo claro
- Abaixo dos cards, 2 pills de destaque centralizados:
  - 💰 "A partir de **R$ 329/mês** por equipamento"
  - 📋 "Ticket médio: **R$ 3.300/mês**"
- Pills com fundo `#2D1058` e texto branco

---

### Slide 7 — O que está incluso (fundo branco)

- Logo "allu." no topo esquerdo (versão roxa)
- Tag pill roxa: `TUDO INCLUSO`
- Título escuro: **"Uma assinatura. Zero dor de cabeça."**
- Subtítulo cinza: "Tudo que sua empresa precisa para manter o parque tecnológico em ordem."
- Grid 2x3 de cards (6 benefícios), cada um com ícone grande em roxo, título em negrito e descrição curta:
  1. 💻 **Equipamento novo** — "Notebooks Acer ou iPhones direto de fábrica, sem recondicionados."
  2. 🔧 **Suporte técnico** — "Atendimento humanizado com SLA de resolução em até 48 horas."
  3. 🔄 **Substituição garantida** — "Equipamento com problema? Mandamos um substituto em até 48h."
  4. 🛡️ **Seguro incluso** — "Cobertura para danos acidentais e roubo no contrato."
  5. 📊 **Portal de gestão** — "Gerencie contratos, equipamentos e colaboradores em um painel centralizado."
  6. 📈 **Escala com você** — "Aumentou o time? Adicionamos novos equipamentos sem burocracia."
- Cards com borda sutil cinza, border-radius 14px, hover com sombra suave

---

### Slide 8 — CAPEX → OPEX (fundo escuro `#1A0A3B`)

- Logo "allu." no topo esquerdo
- Tag pill: `VANTAGEM FINANCEIRA`
- Título branco: **"Pare de imobilizar capital em equipamentos."**
- Subtítulo cinza claro: "Transforme CAPEX em OPEX e libere caixa para o que realmente importa."

- Tabela comparativa com 3 colunas:
  - Coluna 1 (labels): lista de critérios
  - Coluna 2 "Compra (CAPEX)": resultado para cada critério
  - Coluna 3 "allu. Locação (OPEX)": resultado para cada critério — com destaque visual (fundo roxo sutil)

  Critérios e valores:
  | Critério | Compra (CAPEX) | allu. Locação (OPEX) |
  |---|---|---|
  | Investimento inicial | Alto (R$ 5k–10k/unidade) | Zero |
  | Previsibilidade de custo | Baixa | Alta — parcela fixa mensal |
  | Equipamento sempre atualizado | Não | Sim — upgrade no fim do contrato |
  | Suporte e manutenção | Custo adicional | Incluso |
  | Dedutível de impostos (IRPJ, CSLL, PIS, COFINS) | Parcialmente | 100% do valor da parcela |
  | Gestão de ativos | Manual / sem visibilidade | Portal centralizado |
  | Escalabilidade | Lenta e cara | Imediata |

  - Coluna CAPEX: ícone ❌ vermelho para cada desvantagem
  - Coluna allu.: ícone ✅ verde para cada vantagem
  - Cabeçalho da coluna allu. com fundo `#6B21D9`

---

### Slide 9 — Por que a allu. (fundo branco)

- Logo "allu." no topo esquerdo (versão roxa)
- Tag pill roxa: `NOSSOS DIFERENCIAIS`
- Título escuro: **"O que nos torna diferentes de qualquer outra opção."**
- 4 cards grandes em grid 2x2, cada um com ícone, título e parágrafo curto:
  1. 🤝 **Parceria com a Acer** — "Acesso direto ao fabricante significa equipamentos premium, preços competitivos e condições exclusivas que nenhuma locadora comum consegue oferecer."
  2. 🔁 **Economia circular** — "Após o contrato, os equipamentos são recuperados, reformados e realocados. Bom para o seu bolso e para o planeta."
  3. ❤️ **Atendimento humanizado** — "Nada de chatbot. Nossa equipe B2B acompanha você do onboarding ao fim do contrato, com conta dedicada."
  4. 📱 **Ecossistema completo** — "Notebook ou iPhone, do estagiário ao C-level — temos o equipamento certo para cada perfil de colaborador."
- Cards com borda sutil cinza, border-radius 16px, hover com leve sombra roxa

---

### Slide 10 — Próximos Passos / CTA (fundo roxo `#6B21D9`)

- Logo "allu." no topo esquerdo (branco)
- Centralize verticalmente:
  - Ícone grande de foguete 🚀 ou similar, branco
  - Título branco grande: **"Pronto para equipar seu time com o que há de melhor?"**
  - Subtítulo branco com opacidade 0.85: "Vamos montar uma proposta customizada para a sua empresa."
  - 3 cards menores em linha com os próximos passos:
    1. 📋 **Diagnóstico** — "Você nos conta o tamanho do time e os equipamentos necessários."
    2. 📄 **Proposta em 24h** — "Enviamos uma proposta detalhada com valor por unidade e total mensal."
    3. ✅ **Assinatura e entrega** — "Contrato assinado, equipamentos entregues em até 5 dias úteis."
  - Cards com fundo `rgba(255,255,255,0.15)`, borda `rgba(255,255,255,0.25)`, texto branco
  - Botão CTA grande e branco (texto roxo): **"Solicitar proposta agora"** — link para `https://www.alluempresas.com`
  - Abaixo do botão, em texto bem pequeno branco com opacidade 0.7: `alluempresas.com  |  contato@allu.com.br`

---

## Comportamento e UX

- Navegação por **setas do teclado** (← →) e **botões visuais** no rodapé (chevron-left / chevron-right do lucide-react)
- **Barra de progresso** fina no topo da tela, em roxo `#6B21D9`, avançando conforme os slides
- **Contador de slides** no rodapé centralizado: "3 / 10" em texto pequeno
- **Transição suave** entre slides (fade ou slide horizontal) com ~300ms
- Todos os slides devem **ocupar 100vw × 100vh**, sem scroll vertical
- O conteúdo de cada slide deve **caber na tela** sem precisar rolar
- Adicione um **botão fullscreen** discreto no canto superior direito (ícone maximize do lucide)
- **Responsivo para 1280x720** no mínimo (uso em chamadas de vídeo via compartilhamento de tela)

---

## Stack técnica sugerida

- React + TypeScript
- Tailwind CSS
- lucide-react (ícones)
- framer-motion (transições suaves entre slides)
- Fonte Inter via Google Fonts

---

## Observações finais

- Não use imagens externas — use apenas ícones lucide e tipografia para montar o visual
- Cada slide deve ser um componente separado
- Mantenha o código limpo e organizado por slide
- O slide 3 (Investigação) tem uma nota interna para o vendedor — pode deixar num tom levemente diferente (ex: borda ou tag "Uso interno")
- A apresentação será usada em chamadas de vídeo (Google Meet, Zoom), então legibilidade em tela compartilhada é prioridade
