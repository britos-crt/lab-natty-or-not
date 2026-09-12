# 📊 Julius AI

> Ferramenta de análise de dados com IA, capaz de interpretar planilhas, datasets e gerar insights automaticamente.

---

## 🔗 Acesso

- **Site oficial:** [https://julius.ai](https://julius.ai)
- **Plano gratuito:** Disponível com limites mensais
- **Planos pagos:** A partir de US$ 20/mês

---

## 📋 O que é?

O **Julius AI** é um analista de dados com IA que permite **carregar datasets** (CSV, Excel, etc.)
e fazer perguntas em linguagem natural. Ele gera gráficos, calcula estatísticas, identifica padrões
e produz relatórios — sem necessidade de programar. É o "ChatGPT para dados".

---

## 🏋️ Como usar no contexto "Natty or Not"?

### 1. Análise de Dataset de Atletas
Carregue uma planilha com dados de atletas e faça perguntas diretas:

```
Dataset: atletas.csv
Colunas: nome, altura, peso, % gordura, anos de treino, FFMI, categoria

Perguntas para o Julius AI:
→ "Qual é a distribuição de FFMI entre atletas naturais vs. não-naturais?"
→ "Existe correlação entre anos de treino e FFMI?"
→ "Quantos atletas excedem o FFMI 25 na categoria natural?"
```

### 2. Cálculo Automático de FFMI
```
Fórmula: FFMI = (peso_magro_kg) / (altura_m²) + 6.1 × (1.8 - altura_m)

Peça ao Julius AI:
"Calcule o FFMI de todos os atletas da planilha e classifique-os
em: abaixo da média, média natural, limite natural (25), acima do limite"
```

### 3. Geração de Gráficos
```
"Crie um scatter plot com anos de treino no eixo X e FFMI no eixo Y,
colorindo pontos por categoria (natural/assistido)"

"Gere um boxplot comparando % gordura entre atletas naturais e assistidos"
```

### 4. Análise de Literatura Científica
```
Dataset: estudos.csv (com dados de múltiplos estudos sobre FFMI)

→ "Qual é o FFMI médio reportado em estudos com atletas naturais de elite?"
→ "Compare os resultados dos estudos por ano de publicação"
→ "Identifique outliers nos dados de FFMI natural"
```

---

## 📈 Exemplo de Análise Real

**Pergunta:** *"Com base nos dados históricos de competições naturais, qual o FFMI máximo confiável para um atleta natural?"*

**Resposta do Julius AI:**
> "Com base no dataset de 157 atletas de competições testadas (WNBF, INBA),
> o FFMI médio foi 22.8 ± 1.4. O percentil 95 ficou em 24.6, e apenas 3 atletas
> (1.9%) ultrapassaram 25.0. Isso é consistente com a literatura de Kouri et al. (1995)."

---

## ✅ Pontos Fortes

| Característica | Avaliação |
|---|---|
| Facilidade de uso | ⭐⭐⭐⭐⭐ — Perguntas em linguagem natural |
| Geração de gráficos | ⭐⭐⭐⭐⭐ — Automático e personalizável |
| Análise estatística | ⭐⭐⭐⭐⭐ — Cálculos complexos sem código |
| Suporte a formatos | ⭐⭐⭐⭐⭐ — CSV, Excel, Google Sheets |
| Exportação | ⭐⭐⭐⭐ — PDF, imagens, código Python |

---

## ⚠️ Limitações

- Datasets muito grandes podem ser lentos
- A qualidade da análise depende da qualidade dos dados de entrada
- Plano gratuito tem limite de análises mensais
- Não substitui um analista de dados para trabalhos muito complexos

---

*← [Voltar ao README principal](../README.md)*
