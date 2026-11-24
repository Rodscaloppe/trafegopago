# Etapa 04.1 — Meta Ads (Facebook & Instagram): Hierarquia, Objetivos e Orçamento

## 1. A Hierarquia das 3 Camadas do Meta Ads

Toda campanha no Gerenciador de Anúncios da Meta é organizada como uma **árvore de 3 níveis**. Saber o que configurar em cada nível é 50% do domínio da ferramenta:

```
+=======================================================================+
| NÍVEL 1: 📁 CAMPANHA ("O Quê e Quanto?")                              |
| - Qual é o Objetivo final? (Vendas, Leads, Engajamento, Tráfego...)   |
| - O orçamento será distribuído pela Campanha (CBO) ou Conjunto (ABO)? |
+=======================================================================+
                   |                                   |
                   v                                   v
+----------------------------------+ +----------------------------------+
| NÍVEL 2: 📂 CONJUNTO 01 ("Quem,  | | NÍVEL 2: 📂 CONJUNTO 02          |
|          Onde e Quando?")        | |          (Outro Público)         |
| - Local da Conversão (Site/Whats)| | - Público: Lookalike 1% Compras  |
| - Evento do Pixel (Compra/Lead)  | | - Idade: 25 a 55 anos, Mulheres  |
| - Público: Interesses Estética   | | - Posicionamentos: Automático    |
| - Posicionamento: Reels + Stories| | - Programação de Horário         |
+----------------------------------+ +----------------------------------+
         |                 |                          |
         v                 v                          v
+-----------------+ +-----------------+      +-----------------+
| NÍVEL 3: 🖼️ AD 1| | NÍVEL 3: 🎬 AD 2|      | NÍVEL 3: 🎬 AD 1|
| ("O Que Vêem?") | |                 |      |                 |
| - Vídeo 01      | | - Imagem 02     |      | - Vídeo 01      |
| - Copy + Título | | - Copy + Título |      | - Copy + Título |
| - Link + UTMs   | | - Link + UTMs   |      | - Link + UTMs   |
+-----------------+ +-----------------+      +-----------------+
```

---

## 2. Os 6 Objetivos de Campanha (ODAX) — Qual Escolher?

A Meta simplificou o gerenciador em **6 objetivos oficiais**. Mas atenção: **o algoritmo entrega exatamente o que você pede**. Se você pedir "Tráfego (Cliques)", ele vai mostrar seu anúncio para "clicadores compulsivos" que clicam em tudo e não compram nada!

| Objetivo no Gerenciador | O que o Algoritmo busca? | Quando USAR na prática? | Quando NÃO usar? |
| :--- | :--- | :--- | :--- |
| **1. Vendas** *(Sales)* | Pessoas com histórico de **comprar online** ou converter em sites | **E-commerce, Infoprodutos, Landing Pages de alta intenção** e até WhatsApp otimizado para conversão | Para ganhar seguidores ou curtidas no post |
| **2. Cadastros** *(Leads)* | Pessoas propensas a preencher formulários ou iniciar contato qualificado | **Captação de Leads (Landing Page, Formulário Instantâneo Nativo ou WhatsApp)** para negócios locais, imóveis, B2B | Para vender produtos de e-commerce direto no carrinho |
| **3. Engajamento** | Pessoas que mandam mensagens, curtem, comentam ou assistem vídeos | **Campanhas de Mensagens para WhatsApp / Direct**, ou distribuição de conteúdo em vídeo (Video View) e ganho de seguidores | Para mandar pessoas para comprar em um site externo |
| **4. Tráfego** | Pessoas que **clicam em links** pelo menor preço possível | Visitas ao perfil do Instagram (atalho) ou leitura de artigos de blog onde não há conversão com Pixel | ❌ **NUNCA use Tráfego esperando vendas numa Landing Page!** Use *Vendas* ou *Cadastros*. |
| **5. Reconhecimento** | Mostrar o anúncio o máximo de vezes pelo menor CPM | Grandes marcas locais que querem apenas ser lembradas em um raio de 2km (outdoor digital) | Quando você precisa de retorno financeiro imediato (vendas/leads) |
| **6. Promoção do App** | Pessoas propensas a baixar aplicativos na App Store / Google Play | Empresas donas de aplicativos mobile (iOS/Android) | Qualquer negócio que não seja um aplicativo mobile |

---

## 3. ABO vs. CBO (Orçamento Advantage+): Qual a Diferença?

Onde você define o dinheiro da campanha? Existem duas modalidades:

```
+-----------------------------------+-----------------------------------+
|   🎛️ ABO (Ad Set Budget Opt.)     |   🤖 CBO / Advantage+ Budget      |
|  Orçamento no NÍVEL DO CONJUNTO   |  Orçamento no NÍVEL DA CAMPANHA   |
+-----------------------------------+-----------------------------------+
|         [ CAMPANHA ]              |      [ CAMPANHA: R$ 100/dia ]     |
|          /        \               |            /             \        |
|         v          v              |           v               v       |
|  [Conj. A]        [Conj. B]       |    [Conj. A]           [Conj. B]  |
|  R$ 50/dia        R$ 50/dia       |  (Algoritmo dá       (Algoritmo dá|
|  (Garantido)      (Garantido)     |   R$ 82 aqui)         R$ 18 aqui) |
+-----------------------------------+-----------------------------------+
```

### Quando usar cada um?

* **Use ABO (Orçamento no Conjunto) quando:**
  1. Você está **testando novos públicos** (ex.: quer obrigar a Meta a gastar exatamente R$ 30 no público de *Advogados* e R$ 30 no público de *Médicos* para comparar de forma justa).
  2. Você está misturando um **Público Frio Gigante** (10 milhões de pessoas) com um **Público de Remarketing Pequeno** (5 mil pessoas) na mesma campanha — se usar CBO aqui, a Meta vai jogar 99% do dinheiro no público grande e ignorar o pequeno.
* **Use CBO (Orçamento Advantage+ na Campanha) quando:**
  1. Você já validou 3 ou 4 públicos que funcionam e têm tamanhos parecidos, e quer deixar o algoritmo distribuir a verba automaticamente para onde o CPA estiver mais barato no dia (**Fase de Escala**).
  2. Você está fazendo teste de criativos com conjuntos de mesmo tamanho.
