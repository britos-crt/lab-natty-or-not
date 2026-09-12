# ⚙️ Stable Diffusion

> Modelo open-source de geração de imagens, executável localmente ou via plataformas online.

---

## 🔗 Acesso

- **Stability AI:** [https://stability.ai](https://stability.ai)
- **Automatic1111 (local):** [https://github.com/AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
- **ComfyUI (local):** [https://github.com/comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- **Online (sem instalação):** [https://stablediffusionweb.com](https://stablediffusionweb.com)

---

## 📋 O que é?

O **Stable Diffusion** é um modelo de geração de imagens **open-source** desenvolvido pela Stability AI.
Diferente do Midjourney e DALL·E, pode ser executado **localmente na sua máquina** (com GPU compatível),
oferecendo total privacidade, sem custos por imagem gerada e máxima customização via LoRA, fine-tuning
e pipelines personalizados.

---

## 🏋️ Como usar no contexto "Natty or Not"?

### 1. Fine-tuning para Análise de Composição Corporal
Com Stable Diffusion, é possível treinar modelos especializados:

```python
# Conceito: treinar um LoRA com imagens de atletas naturais documentados
# para que o modelo aprenda as características visuais típicas
# de fisiculturismo natural vs. assistido
```

### 2. Geração de Datasets Visuais
```
Positive prompt: natural bodybuilder, realistic muscle definition,
moderate vascularity, healthy skin tone, competition stage,
professional photography, 8k

Negative prompt: unrealistic proportions, extreme vascularity,
paper-thin skin, synthetic look
```

### 3. Análise com ControlNet
O módulo **ControlNet** permite:
- Detectar poses corporais a partir de fotos reais
- Gerar variações mantendo a proporção exata do corpo
- Comparar composições corporais de forma objetiva

### 4. Img2Img para Comparativos
Use a função **img2img** para:
```
Carregar foto de atleta → Gerar versão "natural normalizada"
→ Comparar visualmente as diferenças de proporção
```

---

## 🛠️ Configuração Básica (local)

```bash
# Instalação via git (requer Python 3.10+ e GPU NVIDIA)
git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui
cd stable-diffusion-webui
./webui.sh  # Linux/Mac
# webui-user.bat  # Windows
```

**Requisitos mínimos:**
- GPU NVIDIA com 4GB+ VRAM (6GB+ recomendado)
- 16GB RAM
- ~10GB espaço em disco por modelo

---

## ✅ Pontos Fortes

| Característica | Avaliação |
|---|---|
| Gratuito | ⭐⭐⭐⭐⭐ — Open-source, sem custo por imagem |
| Customização | ⭐⭐⭐⭐⭐ — LoRA, fine-tuning, pipelines |
| Privacidade | ⭐⭐⭐⭐⭐ — Execução 100% local |
| Comunidade | ⭐⭐⭐⭐⭐ — Civitai, HuggingFace, GitHub |
| Controle técnico | ⭐⭐⭐⭐⭐ — Parâmetros granulares |

---

## ⚠️ Limitações

- Requer hardware adequado para execução local
- Curva de aprendizado maior que ferramentas consumer
- Qualidade padrão inferior ao Midjourney sem fine-tuning
- Configuração inicial pode ser complexa

---

*← [Voltar ao README principal](../README.md)*
