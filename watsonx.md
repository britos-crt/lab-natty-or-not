# 🏢 IBM watsonx.ai

> Plataforma empresarial de IA da IBM, com foco em governança, segurança e análise de dados em larga escala.

---

## 🔗 Acesso

- **Site oficial:** [https://www.ibm.com/watsonx](https://www.ibm.com/watsonx)
- **Console:** [https://dataplatform.cloud.ibm.com](https://dataplatform.cloud.ibm.com)
- **Modelos disponíveis:** Granite (IBM), Llama 3, Mistral, e outros via model hub

---

## 📋 O que é?

O **IBM watsonx.ai** é uma plataforma de IA generativa voltada para **uso empresarial**, com ênfase em
transparência, rastreabilidade e governança de dados. Oferece um studio para treinar, ajustar e implantar
modelos de linguagem, além de ferramentas para análise de dados estruturados com IA.

---

## 🏋️ Como usar no contexto "Natty or Not"?

### 1. Análise de Dados de Atletas
Com o watsonx.ai, você pode processar datasets de atletas para identificar padrões:

```python
# Exemplo conceitual com watsonx.ai Python SDK
from ibm_watsonx_ai import APIClient
from ibm_watsonx_ai.foundation_models import ModelInference

model = ModelInference(
    model_id="ibm/granite-13b-instruct-v2",
    credentials={"url": "...", "apikey": "..."},
    project_id="..."
)

prompt = """
Analise os seguintes dados de um atleta e avalie a probabilidade de uso de substâncias:
- FFMI: 27.3
- Anos de treino: 5
- % Gordura: 4.2%
- Peso: 95kg | Altura: 1.78m
"""

response = model.generate_text(prompt=prompt)
print(response)
```

### 2. Processamento de Literatura Científica (NLP)
```
Extraia e classifique automaticamente os principais achados de 50 artigos
científicos sobre hipertrofia muscular natural vs. assistida.
```

### 3. Criação de Pipeline de Análise
O watsonx.ai permite criar pipelines completos:
- **Ingestão:** artigos científicos, dados de atletas
- **Processamento:** NLP para extração de entidades
- **Análise:** classificação natural vs. não-natural por FFMI e biomarcadores
- **Relatório:** geração automática de insights

---

## ✅ Pontos Fortes

| Característica | Avaliação |
|---|---|
| Governança e compliance | ⭐⭐⭐⭐⭐ — Auditoria e rastreabilidade |
| Integração empresarial | ⭐⭐⭐⭐⭐ — APIs robustas e seguras |
| Análise de dados | ⭐⭐⭐⭐⭐ — Integrado ao IBM Cloud |
| Variedade de modelos | ⭐⭐⭐⭐ — Modelos IBM e open-source |
| Acessibilidade | ⭐⭐⭐ — Focado em enterprise |

---

## ⚠️ Limitações

- Mais complexo de configurar do que soluções consumer (ChatGPT, Claude)
- Requer conta IBM Cloud e configuração de projeto
- Custo pode ser elevado para uso individual

---

## 💡 Caso de Uso Ideal

O watsonx.ai brilha quando combinado com **grandes volumes de dados estruturados**:
- Análise de datasets de competições de fisiculturismo
- Processamento automático de literatura médica sobre doping
- Construção de sistemas de scoring para classificar atletas por biomarcadores

---

*← [Voltar ao README principal](../README.md)*
