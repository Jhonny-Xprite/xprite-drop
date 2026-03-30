# Project Brief: Xprite-Drop

**Centro de Comando Operacional para Dropshipping com IA**

---

## Executive Summary

**Xprite-Drop** é uma plataforma SaaS com Inteligência Artificial que funciona como um **Centro de Comando Operacional para Dropshipping**, transformando operações fragmentadas em sistemas de execução integrados e escaláveis.

### O Problema

Operações de dropshipping de alta performance enfrentam fragmentação estrutural:
- **Múltiplas ferramentas desconectadas** (Meta ADS, Google ADS, Canvas, Shopify, Yampi, DSers, etc.)
- **Processos espalhados** sem visibilidade integrada
- **Excesso de trabalho manual** (copiar produtos, criar anúncios, gerenciar pedidos)
- **Falta de padrão** — cada etapa opera de forma independente
- **Sem feedback loops** — dados de vendas não informam criação ou anúncios

**Resultado:** Retrabalho, excesso de cliques, perda de tempo, dificuldade em escalar de forma previsível.

### A Solução: Xprite-Drop

Uma plataforma centralizada que **orquestra toda a operação de dropshipping** — da mineração até pós-venda — em um sistema único com inteligência artificial integrada em cada etapa.

**Núcleo:** Estruturar squads especializados (humanos + IA) que trabalham em uma esteira operacional clara:

1. **Planejamento** — Análise de mercado, tendências, oportunidades
2. **Criação** — Geração de produtos, imagens, descrições (com IA)
3. **Veiculação** — Criação e otimização de campanhas (Meta ADS, Google ADS)
4. **Mensuração** — Tracking de resultados, ROI, performance por produto
5. **Pedidos** — Gerenciamento centralizado (Shopify, Yampi, Appmax)
6. **Suporte** — Atendimento integrado com histórico de pedidos e cliente
7. **Pós-venda** — Follow-up, retenção, analytics de satisfação

**Diferencial:** Integração profunda com toda stack de ferramentas (Meta ADS, Google ADS, Shopify, Yampi, Canvas, DSers, BK-Reviews, etc.) + **feedback loops inteligentes** que conectam resultados de vendas com otimização de criação e anúncios.

### Mercado-Alvo

**Primário:** Empreendedores e gestores de operações e-commerce/dropshipping de **alta performance**
- Operações Shopify/Yampi com múltiplas lojas
- Equipes que já ultrapassaram fase de improviso
- Buscam industrializar (sair do modelo artesanal)

**Perfil:**
- Faturamento: R$ 100k - R$ 5M+/mês
- Equipe: 3-20+ pessoas
- Dor: Velocidade, padronização, escalabilidade, menos trabalho manual
- Sofisticação: Já usam múltiplas ferramentas, entendem funnel de vendas

### Proposta de Valor

| Aspecto | Antes (Fragmentado) | Depois (Xprite-Drop) |
|--------|-------------------|---|
| **Tempo de criação** | 30+ min por produto | 5 min (com IA) |
| **Cliques por etapa** | 50+ cliques para publicar anúncio | 5 cliques (orquestrado) |
| **Visibilidade** | Ferramentas isoladas, sem contexto | Visão 360° da operação |
| **Padrão** | Cada pessoa faz do seu jeito | Processo padronizado |
| **Feedback** | Vendas não informam criação | Loop contínuo inteligente |
| **Escalabilidade** | Manual até quebrar | Sistemática e previsível |

**Resultado:** Uma operação que antes era **caótica e dependente de trabalho manual** passa a funcionar como um **sistema operacional integrado** — mais rápido, com menos atrito, maior padronização e escalabilidade matemática.

---

## Posicionamento Competitivo

### Análise de Mercado

**Competidores Principais:**
- **Oberlo:** Mineração + Shopify plugin (sem automação de anúncios)
- **DSers:** Plugin Shopify para fulfillment (sem orquestração de criação)
- **Spocket:** Sourcing curado (sem IA, sem automação)
- **Printful:** Fulfillment + branding (foco em print, não performance)
- **Make/Integromat:** Automação genérica (sem contexto dropshipping)

### Diferencial Competitivo do Xprite-Drop

**Nenhum competidor oferece:**
1. ✅ **Orquestração completa** (mineração → criação → anúncios → pedidos → suporte → pós-venda)
2. ✅ **IA integrada em toda esteira** (não apenas automação, mas decisão inteligente)
3. ✅ **Estrutura de squads** (humanos + IA trabalhando juntos no mesmo sistema)
4. ✅ **Feedback loops inteligentes** (vendas informam criação, criação informa anúncios)
5. ✅ **Visão operacional unificada** (uma source of truth para toda operação)

**Posicionamento:** Xprite-Drop é o **"Salesforce do Dropshipping"** — CRM operacional + automação + IA para toda esteira de execução.

---

## Arquitetura de Integrações

### Ferramentas de Sincronização Crítica

#### 📦 **MINERAÇÃO & SOURCING**
- **Aliexpress** → Buscar produtos, preços, fornecedores
- **Dropar-Me** → Mineração de tendências, produtos trending
- **Integração:** Sincronizar catálogo em tempo real → identificar oportunidades

#### 🎨 **CRIAÇÃO & DESIGN**
- **Canvas** → Template de design, imagens, mockups
- **Integração:** IA gera briefing → Canvas cria visuals → sistema aprova/publica

#### 📢 **VEICULAÇÃO & ANÚNCIOS**
- **Meta ADS** → Campanhas Facebook/Instagram
- **Google ADS** → Search e Display
- **Integração:** Sistema otimiza copy, audience, bid → monitora performance → feedback para criação

#### 🏪 **LOJA & CHECKOUT**
- **Shopify** → Loja principal, catálogo
- **Yampi** → Checkout otimizado
- **Appmax** → Checkout alternativo
- **Integração:** Sincronizar inventário, pedidos, clientes em tempo real

#### 🛠️ **PLUGINS SHOPIFY**
- **DSers** → Gerenciamento de fulfillment
- **BK-Reviews** → Reviews e social proof
- **Integração:** Puxar dados de qualidade de fornecedor → informar sourcing

#### 📊 **MENSURAÇÃO & ANALYTICS**
- **Meta Ads Manager API** → Performance de campanhas
- **Google Analytics API** → Comportamento de usuário
- **Shopify Admin API** → Vendas, LTV, AOV
- **Integração:** Dashboard unificado com métricas de todas as fontes

#### 💬 **SUPORTE & PÓS-VENDA**
- **Whatsapp (via Shopify)** → Atendimento integrado
- **Email** → Automações de follow-up
- **Integração:** Histórico de pedido + contexto de cliente → atendimento informado

---

## Fluxo de Operação: Antes vs. Depois

### ❌ ANTES: Fragmentado

```
Aliexpress ──┐
Dropar-Me    ├─→ [Gerente] ──→ Canvas ──→ [Designer] ──→ Meta ADS ──→ [Expert ADS]
BK-Reviews   │                                                              │
             └─────────────────────────────────────────────────────────────┘
                           (Sem feedback, sem integração)

                    Shopify ──→ [Gerente de Pedidos] ──→ DSers ──→ Fornecedor
                    Yampi       (cria ticket manual)
```

**Resultado:** Múltiplos pontos de atrito, retrabalho, sem visão integrada.

### ✅ DEPOIS: Orquestrado com Xprite-Drop

```
                        ┌─────────────────────────────────┐
                        │  XPRITE-DROP (Centro de Comando) │
                        └─────────────────────────────────┘
                                      │
        ┌─────────────┬───────────────┼───────────────┬─────────────┐
        ↓             ↓               ↓               ↓             ↓
   MINERAÇÃO    CRIAÇÃO         VEICULAÇÃO      PEDIDOS          SUPORTE
   (Squad 1)    (Squad 2)       (Squad 3)      (Squad 4)        (Squad 5)

Aliexpress    Canvas          Meta ADS        Shopify      Whatsapp/Email
Dropar-Me  → [IA gera]   →   Google ADS  →   Yampi    →   [Atendimento]
BK-Reviews    briefing        [Otimiza]       Appmax       integrado
              [Designer         bid/copy      [Sincroniza
              refina]          [Tracks]        pedidos]

   ↓             ↓               ↓               ↓             ↓
        ┌─────────────────────────────────────────────────┐
        │   FEEDBACK LOOPS INTELIGENTES (IA)              │
        │   - Qual produto vende mais?                    │
        │   - Qual anúncio tem melhor ROAS?              │
        │   - Que tipo de criação converte mais?         │
        └─────────────────────────────────────────────────┘
```

**Resultado:** Uma esteira de produção clara, com IA informando cada decisão, humanos focando no que importa, feedback contínuo otimizando todo sistema.

---

## Target Users

### Segmento Primário: Operador de Alta Performance

**Perfil:**
- 28-45 anos, empreendedor ou gestor sênior
- Já faturou R$ 100k+ em dropshipping
- Tem equipe (3-20+ pessoas)
- Frustrado com fragmentação de ferramentas
- Entende funnel de vendas e ROAS

**Dores:**
- "Minha equipe passa 40% do tempo em tarefas manuais"
- "Não consigo ver a operação completa em um lugar"
- "Não tenho feedback de qual produto/anúncio realmente funciona"
- "Escalar é caótico — cada novo produto é um drama"
- "Perdi uma oportunidade porque não vi o trend no tempo"

**Desejos:**
- Visão 360° da operação
- Menos cliques, mais automação
- Decisões data-driven
- Escalar de forma previsível
- Focar em estratégia, não em tática

### Segmento Secundário: Agência de Dropshipping

**Perfil:**
- Gerencia múltiplas lojas para clientes
- Precisa de padronização para escalar
- Quer oferecer melhor serviço aos clientes

**Desejos:**
- Dashboard para cada cliente
- Processos padronizados
- Menos time necessário por loja
- Reportagem automática

---

## Goals & Success Metrics

### Business Objectives
- Capturar 5% do mercado de dropshipping BR em 18 meses (~5,000 lojas)
- Gerar ARR de R$ 10M+
- Tornar-se plataforma referência de operação escalável em dropshipping

### User Success Metrics
- **Tempo de operação:** Reduzir em 50% (de 40h para 20h/semana por operação)
- **Taxa de publicação:** Aumentar de 5 para 50+ produtos/dia por operação
- **ROAS:** Melhorar em 30-50% (otimização contínua via feedback loops)
- **Taxa de erro:** Reduzir erros manuais em 80%

### Key Performance Indicators (KPIs)
- **Churn Rate:** < 5% ao mês
- **NPS:** > 50
- **ARPU:** Crescimento de 20% A/A
- **Adoption Rate:** 60%+ dos usuários usando 3+ módulos

---

## MVP Scope

### Core Features (Must Have)

1. **Dashboard Centralizado**
   - Visão 360° da operação (mineração, criação, anúncios, vendas, suporte)
   - KPIs em tempo real (vendas, ROAS, LTV, tempo médio de atendimento)
   - Alertas de anomalias (produto de baixa conversão, fornecedor fora de estoque)

2. **Squad de Mineração** (Powered by AliPrice Intelligence)
   - ✨ **Busca Reversa por Imagem:** Upload de imagem → busca em 10+ plataformas (AliExpress, Taobao, 1688, Pinduoduo)
   - 📈 **Price History Intelligence:** Coleta histórico 6 meses, detecta descontos reais vs. artificiais
   - 🎯 **Smart Supplier Ranking:** Recomenda fornecedor baseado em confiabilidade, velocidade, qualidade (não só preço)
   - 🤖 **AI-Powered Recommendations:** ML model sugere qual produto/fornecedor vai ter melhor ROAS baseado em histórico
   - 📦 **Batch Intelligence:** Upload 50+ imagens → análise paralela → matriz de decisão
   - 🔔 **Trend Mining Automático:** Monitora Dropar-Me + análise de imagem para identificar trends ANTES do concorrente
   - 💡 **Integração com Dropar-Me, AliExpress, Taobao, 1688, Pinduoduo**
   - 📊 **Sincronização de catálogo em tempo real** com dados de preço, fornecedor, tendência
   - 🎨 **Versionamento de sourcing** (quais produtos testou, resultado, feedback)

3. **Squad de Criação**
   - Integração com Canvas
   - IA gera briefing (título, descrição, keywords)
   - Workflow de aprovação
   - Versionamento de criativos

4. **Squad de Veiculação**
   - Integração Meta ADS + Google ADS
   - Criação de campanhas automatizada
   - Otimização de bid/copy com IA
   - Tracking de ROAS por produto/campanha

5. **Squad de Pedidos**
   - Integração Shopify + Yampi + Appmax
   - Dashboard de pedidos pendentes
   - Sincronização com fornecedor (DSers)
   - Alertas de atraso/problema

6. **Squad de Suporte (MVP Basic)**
   - Integração com Whatsapp
   - Histórico de pedido + contexto de cliente
   - Templates de resposta com IA
   - Dashboard de tickets abertos

---

## Estratégia de Mineração Inteligente (AliPrice Research)

**Baseada em deep research da plataforma AliPrice.** Documento completo: `docs/research/aliprice-deep-analysis.md`

### O Problema: Mineração Fragmentada Hoje

Operadores de dropshipping gastam **15-30 min por produto** em:
```
1. Ver trending no TikTok/Instagram
2. Procurar em AliExpress (não encontra)
3. Procurar em Taobao (acha similar mas não exato)
4. Procurar em 1688 (ainda outro preço)
5. Comparar fornecedores manualmente
6. Decidir se preço está bom (sem histórico)
7. Importar para loja
8. Ninguém rastreia: "aquele produto vendeu?"
```

**Resultado:** Muitos produtos ruins importados, perdendo dinheiro em anúncios ruins.

### A Solução: Mineração Inteligente do Xprite-Drop

**Fluxo transformado:**
```
Operador vê trending
       ↓
Screenshot imagem OU salva imagem
       ↓
UPLOAD NO XPRITE-DROP (1 clique)
       ↓
┌─────────────────────────────────────┐
│ BUSCA REVERSA INTELIGENTE            │
│ - Busca em paralelo: 10+ plataformas │
│ - Retorna: preço, fornecedor, reviews│
│ - Mostra histórico de preço (6 meses)│
│ - Detecta: preço real vs. artificial │
└─────────────────────────────────────┘
       ↓
┌─────────────────────────────────────┐
│ ML RANKING DE FORNECEDOR             │
│ Input histórico de vendas:           │
│ - Qual fornecedor = menos chargeback?│
│ - Qual preço = melhor conversão?     │
│ - Qual imagem = mais vendas?         │
│                                     │
│ Output: "Fornecedor X: ROAS 2.1 ✓"   │
└─────────────────────────────────────┘
       ↓
OPERADOR: 1 clique → IMPORTA COM CONFIANÇA
       ↓
┌─────────────────────────────────────┐
│ FEEDBACK LOOP                       │
│ Sistema rastreia:                   │
│ - Cliques no anúncio                │
│ - Conversão                         │
│ - Reviews do cliente                │
│ - Chargeback/devolução              │
│                                     │
│ ML Model aprende:                   │
│ "Imagens com característica X       │
│  + fornecedor Y + preço Z = ROAS W"  │
└─────────────────────────────────────┘
```

**Tempo: 15-30 min → 2-3 min (10x mais rápido)**

### 5 Capacidades Principais

#### 1️⃣ Busca Reversa por Imagem (MVP-1)

**O que faz:**
- Operador faz upload de screenshot de trending
- Sistema busca em paralelo: AliExpress, Taobao, 1688, Pinduoduo, Amazon
- Retorna top 10-20 produtos similares com preço + fornecedor + reviews

**Impacto:**
- ⚡ 15 min → 1 min (mineração ultrarrápida)
- 🎯 Padroniza descoberta de produto
- 💾 Cada busca alimenta dados para IA

**Tecnologia:**
- Google Cloud Vision API (feature extraction)
- APIs de cada plataforma (paralelo)
- Redis cache (30 dias)

---

#### 2️⃣ Price History Intelligence (MVP-1)

**O que faz:**
- Coleta preço histórico de cada produto (últimos 6 meses)
- Mostra gráfico visual de flutuações
- Alerta: "Preço está 20% abaixo da média → oportunidade!"
- Alerta: "Preço inflado artificialmente (histórico: R$ 10, hoje: R$ 25) → skip"

**Impacto:**
- 💰 Reduz margem perdida por mau timing
- 🛡️ Protege contra fraudes de preço
- 📊 Educação do operador (aprende padrões)

**Tecnologia:**
- Cron job coleta preços diários
- TimeSeries database (InfluxDB)
- Detecção de anomalias (zscore/isolation forest)

---

#### 3️⃣ Smart Supplier Ranking (MVP-1)

**O que faz:**
- Não mostra só preço → mostra **score composto**:
  - Confiabilidade (taxa de cancelamento)
  - Velocidade (tempo médio até enviar)
  - Qualidade (taxa de devolução/reviews)
  - Estabilidade de preço

**Card visual:**
```
FORNECEDOR A         FORNECEDOR B (⭐ RECOMENDADO)
Preço: R$ 10        Preço: R$ 12
⚠️ Cancelamento: 15% ✅ Cancelamento: 2%
Envio: 20 dias      Envio: 8 dias
Reviews: 3.2★       Reviews: 4.7★
Score: 45/100       Score: 89/100
```

**Impacto:**
- ✅ Reduz chargeback
- ✅ Melhora NPS (cliente recebe produto bom)
- ✅ Menos carga de suporte

---

#### 4️⃣ AI Supplier Recommendation (MVP-1 ou Fase 1)

**O que faz:**
```
Upload imagem de fone de ouvido (preço ~R$ 20-30)
        ↓
ML Model analisa histórico:
"Para imagens similares nessa faixa de preço:"
        ↓
- Fornecedor A: ROAS esperado 1.8
- Fornecedor B: ROAS esperado 2.1 ← RECOMENDADO
- Fornecedor C: ROAS esperado 1.3
        ↓
Operador: 1 clique no recomendado
```

**Impacto:**
- 🚀 Maior ROAS (máximo impacto em receita)
- 🤖 Automação inteligente (máquina sugere, humano aprova)
- 📈 Feedback loop treina modelo continuamente

**ML Model:**
- Features: características da imagem (CNN) + categoria + preço + fornecedor
- Target: ROAS histórico
- Algorithm: LightGBM/XGBoost
- Retraining: semanal (novos dados de vendas)

---

#### 5️⃣ Batch Intelligence (MVP-1 ou Fase 1)

**O que faz:**
```
Operador tem 50 imagens para validar
        ↓
Drag-drop 50 imagens no Xprite-Drop
        ↓
Sistema processa em paralelo (5-10 workers)
        ↓
2 MINUTOS DEPOIS:
┌──────────────────────────────────────┐
│ Matriz de decisão:                   │
├──────────────────────────────────────┤
│ Produto  │ Fornecedor | ROAS | Ação │
├──────────────────────────────────────┤
│ Fone A   │ B (88/100) │ 2.1 │ ✅    │
│ Teclado  │ A (45/100) │ 1.3 │ ⏸️    │
│ Mouse    │ C (92/100) │ 2.3 │ ✅    │
│ ...      │ ...        │ ... │ ...  │
└──────────────────────────────────────┘
```

**Impacto:**
- ⚡ 50x mais rápido (1 hora → 2 minutos)
- 📈 10x mais escalável (mesmo operador valida 500 produtos/dia)
- 🎯 Padronização (mesmos critérios para todos)

---

### Fluxo Integrado: Mineração → Veiculação → Feedback

```
SQUAD MINERAÇÃO
  ├─ Busca imagem
  ├─ Coleta preço histórico
  ├─ Recomenda fornecedor (ML)
  └─ Import com confiança
       ↓
SQUAD CRIAÇÃO
  ├─ IA gera briefing baseado em produtos similares
  └─ Designer cria visual
       ↓
SQUAD VEICULAÇÃO
  ├─ Análise de preço informa CPC bid
  ├─ Histórico de imagens similares informa targeting
  └─ Campaign gerada automática
       ↓
FEEDBACK LOOP (IA treina continuamente)
  ├─ Qual imagem = melhor ROAS?
  ├─ Qual fornecedor = menos chargeback?
  ├─ Qual preço = melhor conversão?
  └─ ML model aprende para próxima decisão
```

### Quick Wins: Implementação por Fase

**MVP-1 (Semanas 3-8):**
- ✅ Busca reversa por imagem
- ✅ Price history dashboard
- ✅ Supplier comparison card

**Fase 1 (Semanas 9-14):**
- ✅ Batch image processing
- ✅ AI supplier recommendation
- ✅ Trend mining automático

**Fase 2 (Semanas 15+):**
- ✅ Price optimization engine (qual preço ideal)
- ✅ Campaign generation AI (copy + targeting automático)
- ✅ Full feedback loop (circulação contínua de dados → IA)

---

### Out of Scope for MVP
- Análise de competidor em tempo real
- IA generativa de imagens/vídeos (apenas briefing)
- Integração com Tiktok ADS
- Analytics avançado (coorte, retention)
- Sistema de pagamento para fornecedores

### MVP Success Criteria
- MVP rodando com 3+ operações de teste por 30 dias
- Feedback positivo em tempo de operação (redução de 30%+)
- Estabilidade: 99.5% uptime
- Capacidade de lidar com 1,000+ produtos sincronizados

---

## Post-MVP Vision

### Phase 2 Features
- **IA Generativa de Criativos:** Gerar imagens/vídeos automáticos
- **Analytics Avançado:** Cohort analysis, retention, LTV por fonte
- **Integração Tiktok ADS:** Veiculação expandida
- **Smart Automation:** Regras customizáveis para cada operação
- **Marketplace de Fornecedores:** Avaliação e recomendação

### Long-term Vision (1-2 anos)
Xprite-Drop como **Operating System para dropshipping** — plataforma que substitui a necessidade de 80% das ferramentas atuais (Meta ADS, Google ADS, Shopify, DSers, etc.), mantendo integrações onde necessário.

**Ecosistema:** Plugins de terceiros, templates de operação, academy de treinamento.

### Expansion Opportunities
- **B2B2C:** White-label para agências
- **Cursos/Academy:** Treinamento em operação sistemática
- **Serviço Gerenciado:** Xprite-Drop roda sua operação por você
- **Mercados Internacionais:** Expandir para e-commerce em geral (não só dropshipping)

---

## Technical Considerations

### Platform Requirements
- **Target Platforms:** Web (desktop-first), mobile (iOS/Android) para operadores em movimento
- **Browser/OS Support:** Chrome 90+, Firefox 88+, Safari 14+ | Windows/Mac/Linux
- **Performance Requirements:** Dashboard carrega em < 2s, sync em tempo real (< 5s)

### Technology Preferences
- **Frontend:** React/Next.js (SSR para SEO, performance)
- **Backend:** Node.js (JavaScript full-stack) ou Python (FastAPI)
- **Database:** PostgreSQL (relacional) + Redis (cache/real-time)
- **Hosting/Infrastructure:** AWS ou Google Cloud (escalabilidade)
- **Message Queue:** RabbitMQ ou AWS SQS (async jobs, integrações)

### Architecture Considerations
- **Repository Structure:** Monorepo (frontend + backend + services)
- **Service Architecture:** Microservices para cada squad (Mineração, Criação, Veiculação, Pedidos, Suporte)
- **Integration Requirements:** API Gateway + SDK para cada integração (Meta, Google, Shopify, etc.)
- **Security/Compliance:** OAuth2 para autenticação, encryption em trânsito/repouso, compliance LGPD/GDPR

---

## Constraints & Assumptions

### Constraints
- **Budget:** Produto precisa ser rentável com pricing SaaS padrão (R$ 500-2,000/mês)
- **Timeline:** MVP em 4-6 meses, go-to-market em mês 7
- **Resources:** Equipe inicial de 5-8 pessoas (dev, design, product, sales)
- **Technical:** APIs de terceiros têm rate limits — precisa arquitetura robusta de retry/cache

### Key Assumptions
- Mercado de dropshipping BR vai continuar crescendo (baixa penetração vs global)
- Operadores de alta performance vão pagar por plataforma que reduce trabalho manual em 50%
- Integração com ferramentas existentes é possível via APIs (não vai exigir scraping)
- Feedback loops inteligentes vão impactar ROAS positivamente (hipótese a validar)
- Equipes vão adotar nova plataforma se reduzir onboarding (UX/DX crítico)

---

## Risks & Open Questions

### Key Risks
- **Integração API instável:** Mudanças em APIs de Meta/Google podem quebrar sistema
  - *Mitigação:* Abstração de integração, versioning, fallbacks

- **Adoção lenta:** Operadores já têm workflow estabelecido
  - *Mitigação:* Onboarding muito fácil, ROI claro em 30 dias, suporte white-glove

- **Competição:** Shopify ou Meta podem construir essa funcionalidade
  - *Mitigação:* Expertise em dropshipping, comunidade, feedback loops — moat de dados

- **Churn:** SaaS de nicho tem churn alto (operadores deixam dropshipping)
  - *Mitigação:* Expandir para e-commerce em geral (não só dropshipping)

### Open Questions
- Qual é o ideal pricing (por operação, por clique, por vendas)? → **Precisa validar com 10+ potenciais clientes**
- Quanto operadores economizam realmente (tempo vs. custo)? → **Case study com beta testers**
- Qual integração vai ter maior impacto (Meta ADS vs. Mineração)? → **MVP test com beta**
- Como garantir adesão de operadores já saturados de ferramentas? → **Pesquisa de mercado**

### Areas Needing Further Research
- Comportamento de compra de software entre operadores de dropshipping
- Benchmarks de tempo operacional em operações de diferentes tamanhos
- Análise de ciclo de decisão (quanto tempo leva para decidir usar nova plataforma)
- Avaliação de alternativas existentes (DSers, Oberlo como alternativas)

---

## Next Steps

### Immediate Actions
1. Validar problema com 10+ operadores de alta performance (30 min calls)
2. Definir pricing strategy (reunião com PM + finance)
3. Esclarecer arquitetura técnica (reunião com arquiteto)
4. Mapear roadmap detalhado de features para MVP
5. Recrutar early beta testers (3-5 operações para validar em produção)

### PM Handoff
Este Project Brief fornece contexto completo para **Xprite-Drop**. Próxima etapa: criar o **PRD (Product Requirements Document)** que detalha cada feature, user stories, e success criteria. O brief já inclui:

- ✅ Diferencial competitivo claro
- ✅ Mercado-alvo bem definido
- ✅ MVP scope realista
- ✅ Arquitetura técnica de alto nível
- ✅ Integrações críticas mapeadas
- ✅ Riscos e mitigações

**Próximo:** @pm cria o PRD seção por seção com detalhe de features, user stories, e acceptance criteria para cada squad.

---

## Documentação de Pesquisa & Referências

### Deep Research: AliPrice Analysis
- 📁 **Arquivo:** `docs/research/aliprice-deep-analysis.md`
- **Conteúdo:**
  - Análise profunda da plataforma AliPrice
  - 7 etapas de entendimento (features, engenharia reversa, oportunidades)
  - Melhorias estratégicas (como superar AliPrice)
  - Top 5 quick wins implementáveis
  - Roadmap de 24 semanas
  - Impacto esperado em ROAS, tempo de operação, escalabilidade

### Como usar esta documentação
1. **Para MVP Planning:** Consulte seção "Estratégia de Mineração Inteligente" (features MVP-1)
2. **Para Roadmap:** Consulte seção "Fase 1" e "Fase 2" de quick wins
3. **Para Technical Deep Dive:** Consulte `docs/research/aliprice-deep-analysis.md` (seção "Engenharia Reversa")
4. **Para Competitive Analysis:** Consulte seção "Diferencial Competitivo" e "Melhorias Estratégicas"

---

**Documento gerado:** 2026-03-30
**Status:** Draft v2 - Atualizado com AliPrice Research + Estratégia de Mineração Inteligente
**Próximo Responsável:** @pm (PRD Creation)
