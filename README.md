# Projeto 3: Análise do Desempenho Financeiro com SQL — Resumo Executivo

Relatório executivo final desenvolvido para apoiar a diretoria financeira na avaliação da rentabilidade dos mercados internacionais, cruzando dados de receitas, custos de produtos e investimentos em campanhas de marketing de 2017.

---

## 📊 Contexto da Análise
Cruzamos os dados de vendas, custos de produtos e investimentos em marketing de 2017 nos 6 países em que a empresa atua. O objetivo principal foi responder a duas perguntas vitais para o negócio: **Quanto estamos ganhando por país?** e **Quão rentável é cada mercado considerando os gastos de marketing?**

---

## 🔍 Principais Achados
1. **EUA é o mercado líder e mais rentável:** Com US$ 3,35M em vendas e um investimento moderado de US$ 1,92M em mídia, gerou US$ 1,45M de lucro bruto e o maior ROI do grupo (75,8%).
2. **Margem de produto estável:** A margem bruta se mantém consistente em todos os países, variando apenas entre 41,7% (Austrália) e 44,8% (Canadá), o que comprova que o custo operacional do produto não é o gargalo da operação.
3. **Mídia ineficiente na Europa e Canadá:** Países como Reino Unido, Alemanha, França e Canadá receberam orçamentos de marketing elevados (entre US$ 1,8M e US$ 2,3M), mas entregaram retornos baixos (ROI de 17% a 22%).

---

## 💡 Ideias Acionáveis (Recomendações)
* **Redistribuir o orçamento de marketing:** Reduzir investimentos em mercados de menor conversão (como França, Canadá e Alemanha) e alocar esse capital nos EUA e na Austrália, onde a eficiência de retorno é comprovadamente superior.
* **Revisar a estratégia europeia:** Realizar uma auditoria nas campanhas do Reino Unido e Europa para entender os altos custos de aquisição e ajustar os gastos ao tamanho real do faturamento local.

---

## 🧠 Reflexões Analíticas

* **Diferença entre Margem e ROI:** 
  * A **Margem** mede a eficiência do produto, indicando quanto sobra de lucro bruto a cada venda realizada ($Lucro Bruto \div Receita$). 
  * O **ROI** mede a eficiência do marketing, mostrando o retorno gerado para cada dólar investido em campanhas ($Lucro Bruto \div Custo de Campanhas$).
* **Por que o ROI nos EUA é muito mais alto?** 
  * Devido à alta escala de vendas (US$ 3,35M) combinada com um investimento em anúncios proporcionalmente controlado (US$ 1,92M). Em contrapartida, o Reino Unido gastou mais em anúncios (US$ 2,3M) para faturar quase três vezes menos.
* **O que aconteceria com o ROI se o gasto com campanhas aumentasse em 50%?** 
  * Se o orçamento de marketing subir 50% sem que as vendas acompanhem o mesmo ritmo, o ROI cairá em 33,3%, uma vez que o denominador da conta (custo de campanha) aumenta. Para preservar o indicador, o lucro bruto teria que crescer proporcionalmente na mesma proporção.

---

## 🛠️ Tecnologias e Ferramentas
* **SQL** (Manipulação, agregação e cruzamento de bases de dados financeiras)
* **Excel** (Tratamento complementar e modelagem do relatório executivo)
