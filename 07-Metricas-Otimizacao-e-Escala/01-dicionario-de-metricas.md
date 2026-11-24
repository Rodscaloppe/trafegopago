# Etapa 07.1 — Dicionário Completo de Métricas: Como Ler o Gerenciador Sem Se Perder

## 1. Métricas de Tráfego (Secundárias) vs. Métricas de Negócio (Primárias)

O maior erro de um gestor iniciante é comemorar que *"o clique está baratinho (R$ 0,20)"* enquanto o caixa da empresa está no vermelho.

Dividimos as métricas em dois grupos:
1. **Métricas de Negócio (Primárias — As que pagam as contas):** Vendas, Leads, CPA, CPL, ROAS, ROI, CAC, LTV.
2. **Métricas de Tráfego / Diagnóstico (Secundárias — Explicam o porquê o resultado subiu ou caiu):** CPM, Alcance, Frequência, CTR, CPC, Hook Rate, Connect Rate.

```
+-----------------------------------------------------------------------+
|  [CPM / Impressões] ---> [CTR / CPC] ---> [Connect Rate] ---> [CPA / ROAS]
|  (Custo da Vitrine)     (Atratividade     (Velocidade da     (Resultado no
|                          do Anúncio)       Landing Page)      Bolso!)
+-----------------------------------------------------------------------+
```

---

## 2. Tabela Mestra de Todas as Métricas com Fórmulas e Referências (Benchmarks)

| Sigla | Nome Completo | Fórmula Matemática | O que ela realmente significa? | Benchmark (Referência Média) |
| :--- | :--- | :--- | :--- | :--- |
| **CPM** | Custo por Mil Impressões | $\frac{\text{Valor Gasto}}{\text{Impressões}} \times 1.000$ | Quanto a plataforma cobra para mostrar seu anúncio **1.000 vezes** na tela. | R$ 10 a R$ 45 *(varia muito por nicho; finanças/B2B é mais alto)* |
| **FREQ** | Frequência | $\frac{\text{Impressões}}{\text{Alcance}}$ | Quantas vezes, em média, **a mesma pessoa** já viu o seu anúncio. | Público Frio: **1,1 a 2,2**<br>Remarketing (7D): **2,5 a 5,0** |
| **CTR** | Taxa de Cliques *(Click-Through Rate)* *(Sempre use "CTR de Clique no Link")* | $\frac{\text{Cliques no Link}}{\text{Impressões}} \times 100$ | De cada 100 vezes que o anúncio apareceu, quantas vezes clicaram para ir ao seu destino. Mede a **força do seu Criativo**! | Meta Ads: **> 1,0% a 2,5%**<br>Google Search: **> 5,0% a 15%** |
| **CPC** | Custo por Clique no Link | $\frac{\text{Valor Gasto}}{\text{Cliques no Link}}$ | Quanto custou cada pessoa que clicou no botão do seu anúncio. | Meta Ads: R$ 0,50 a R$ 3,00<br>Google Search: R$ 1,00 a R$ 8,00 |
| **Hook Rate** | Taxa de Gancho (3 segundos) | $\frac{\text{Reproduções de Vídeo 3s}}{\text{Impressões}} \times 100$ | De cada 100 pessoas no feed, quantas pararam para ver os primeiros **3 segundos** do seu vídeo. | Bom: **> 25%**<br>Excelente: **> 35%** |
| **Hold Rate** | Taxa de Retenção do Vídeo | $\frac{\text{ThruPlays (15s)}}{\text{Reproduções de 3s}} \times 100$ | Das pessoas que pararam nos 3 segundos, quantas continuaram assistindo ao corpo do vídeo. | Bom: **> 25% a 35%** |
| **Connect Rate** | Taxa de Carregamento da Página | $\frac{\text{Visualizações da Página}}{\text{Cliques no Link}} \times 100$ | Quantos % das pessoas que clicaram realmente esperaram o seu site abrir. | Saudável: **> 75% a 85%**<br>Crítico (Site Lento): **< 60%** |
| **CPL** | Custo por Lead (Cadastro/Conversa) | $\frac{\text{Valor Gasto}}{\text{Total de Leads}}$ | Quanto você pagou por cada contato no WhatsApp ou formulário preenchido. | WhatsApp Local: R$ 3 a R$ 18<br>Lead B2B/Imóvel: R$ 20 a R$ 90 |
| **CPA** | Custo por Aquisição (Custo por Venda) | $\frac{\text{Valor Gasto}}{\text{Total de Vendas}}$ | Quanto você gastou em anúncios para gerar **1 venda concluída**. | **Deve ser sempre menor que a sua Margem de Contribuição!** |
| **ROAS** | Retorno sobre o Gasto em Anúncios | $\frac{\text{Receita Gerada pelos Ads}}{\text{Valor Gasto em Ads}}$ | Para cada R$ 1,00 colocado na campanha, quantos reais voltaram em vendas brutas. | Se gastou R$ 1.000 e vendeu R$ 4.000 -> **ROAS = 4,0** |
| **ROI** | Retorno sobre o Investimento Total | $\frac{\text{Receita} - \text{Custos Totais}}{\text{Custos Totais}} \times 100$ | Mede o lucro real da operação inteira (incluindo custo do produto, imposto, equipe e tráfego). | Positivo acima de 0% |

---

## 3. A Relação Matemática Secreta entre CPM, CTR e CPC

Muitas pessoas perguntam: *"Como eu faço o meu CPC (preço do clique) cair pela metade?"*

Veja como o CPC é apenas o resultado da divisão entre o **CPM** e o **CTR**:

$$\text{CPC} = \frac{\text{CPM}}{10 \times \text{CTR (\%)}}$$

### Exemplo Prático nos Números:
Imagine que o leilão no seu nicho está cobrando um **CPM de R$ 30,00** (para 1.000 impressões):

* **Com um Criativo Fraco (`CTR = 0,5%`):**
  De 1.000 impressões, apenas **5 pessoas clicam**.
  $$\text{CPC} = \frac{\text{R\$ } 30,00}{5 \text{ cliques}} = \text{R\$ } 6,00 \text{ por clique!}$$

* **Trocando por um Criativo Campeão (`CTR = 2,0%`):**
  Mesmo pagando os mesmos R$ 30,00 de CPM, agora **20 pessoas clicam** em 1.000 impressões!
  $$\text{CPC} = \frac{\text{R\$ } 30,00}{20 \text{ cliques}} = \text{R\$ } 1,50 \text{ por clique!}$$

> **Moral da história:** Ao melhorar o seu criativo (dobrando ou quadruplicando o CTR), você coloca **4x mais pessoas dentro da sua loja pelo mesmo orçamento**, sem mexer em um único centavo do leilão!
