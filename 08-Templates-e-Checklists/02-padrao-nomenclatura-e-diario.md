# Etapa 08.2 — Padrão Profissional de Nomenclatura e Diário de Otimização

## 1. Por que Usar um Padrão de Nomenclatura?

Uma conta de anúncios cheia de campanhas chamadas `Campanha Nova - Cópia 2 - Cópia` é impossível de analisar. Quando você bate o olho no Gerenciador, precisa saber **em 2 segundos** qual é a etapa do funil, qual é o objetivo, qual é o público e qual é o criativo.

### O Padrão Universal entre `[Colchetes]`

```
+-----------------------------------------------------------------------+
| 📁 NÍVEL 1: NOME DA CAMPANHA                                          |
| Formato: [ETAPA DO FUNIL] [OBJETIVO] [PRODUTO/OFERTA] [ABO ou CBO]    |
|                                                                       |
| Exemplos Reais:                                                       |
| - [F1 - FRIO] [VENDAS] [CURSO INGLÊS] [CBO]                           |
| - [F2 - MORNO] [LEADS WHATS] [IMPLANTE DENTÁRIO] [ABO]                |
| - [F3 - QUENTE] [REMARKETING 14D] [E-COMMERCE VERÃO] [ABO]            |
+-----------------------------------------------------------------------+
                                   |
                                   v
+-----------------------------------------------------------------------+
| 📂 NÍVEL 2: NOME DO CONJUNTO DE ANÚNCIOS (OU GRUPO DE ANÚNCIOS)       |
| Formato: [NUM] [TIPO DE PÚBLICO] [DETALHE / IDADE / REGIÃO] [POSIC.]  |
|                                                                       |
| Exemplos Reais:                                                       |
| - [01] [ABERTO] [MULHERES 25-50 - RAIO 5KM] [AUTO]                    |
| - [02] [INTERESSES] [ESTÉTICA + BELEZA - BRASIL] [REELS+STORIES]      |
| - [03] [LAL 1%] [COMPRADORES 180D] [AUTO]                             |
| - [04] [RMKT 14D] [INITIATE CHECKOUT - EXCL. PURCHASE 180D] [AUTO]    |
+-----------------------------------------------------------------------+
                                   |
                                   v
+-----------------------------------------------------------------------+
| 🎬 NÍVEL 3: NOME DO ANÚNCIO (CRIATIVO)                                |
| Formato: [AD NUM] [FORMATO] [GANCHO / ÂNGULO] [DATA]                  |
|                                                                       |
| Exemplos Reais:                                                       |
| - [AD 01] [VÍDEO 9:16] [GANCHO DOR NAS COSTAS] [24/11]                |
| - [AD 02] [IMAGEM 4:5] [OFERTA BLACK FRIDAY 40% OFF] [24/11]          |
| - [AD 03] [CARROSSEL] [DEPOIMENTOS ANTES/DEPOIS] [24/11]              |
+-----------------------------------------------------------------------+
```

---

## 2. Template de Diário de Otimização (Logbook do Gestor)

Nunca faça uma alteração em uma campanha sem anotar **o dia, o que você mudou e o motivo**. Caso o resultado piore 3 dias depois, esse diário permite que você saiba exatamente o que desfazer.

Copie a tabela abaixo para o seu Notion, Google Sheets ou arquivo Markdown do cliente:

| Data | Plataforma | Campanha / Conjunto | O que estava acontecendo? (Diagnóstico) | Ação Executada | Resultado após 72h |
| :---: | :---: | :--- | :--- | :--- | :--- |
| `01/12` | Meta Ads | `[F1] [VENDAS]` / Conjunto `02 Interesses` | Gastou R$ 95 (1,5x CPA Ideal) com apenas 0,5% de CTR e 0 vendas. | Pausei `[AD 01]` e subi `[AD 04]` com novo gancho nos primeiros 3s. | CTR subiu para 1,8% e saíram 3 vendas com CPA de R$ 38. |
| `04/12` | Meta Ads | `[F1] [VENDAS]` / Conjunto `01 Aberto` | CPA excelente (R$ 32 vs Meta de R$ 50) nos últimos 4 dias. | Escala Vertical: aumentei orçamento de R$ 50/dia para R$ 65/dia (+30%). | Manteve CPA em R$ 35 com mais volume. |
| `06/12` | Google Ads | `[SEARCH] [FUNDO FUNIL]` | Termos de pesquisa mostraram cliques para *"curso de manutenção"*. | Adicionei `"curso"`, `"aula"` e `"SENAI"` na lista de negativas. | CPC médio caiu 15% e taxa de conversão subiu. |

---

## 3. Template de Colunas Personalizadas no Meta Ads

No Gerenciador de Anúncios da Meta, clique no botão **"Colunas: Desempenho" -> "Personalizar Colunas"** e salve exatamente esta ordem para analisar seu funil da esquerda para a direita como um raio-X:

1. **Veiculação e Orçamento:** `Veiculação`, `Orçamento`, `Valor usado (Valor gasto)`
2. **Entrega e Saturação:** `Impressões`, `Alcance`, `Frequência`, `CPM`
3. **Retenção de Vídeo (se usar vídeos):** `Reproduções de vídeo por no mínimo 3 segundos`, `ThruPlays`
4. **Atratividade do Criativo:** `Cliques no link`, `CTR (taxa de cliques no link)`, `CPC (custo por clique no link)`
5. **Saúde da Página:** `Visualizações da página de destino`, `Custo por visualização da página de destino`
6. **Meio do Funil do Site:** `Adições ao carrinho` (ou `Cadastros`), `Finalizações de compra iniciadas (InitiateCheckout)`, `Custo por finalização de compra iniciada`
7. **Fundo de Funil (Dinheiro no Bolso):** `Compras` (ou `Conversas por mensagem iniciadas`), `Custo por Compra (CPA)`, `Valor de conversão da compra`, `ROAS de compra`
