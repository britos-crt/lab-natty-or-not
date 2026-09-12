# 🎙️ ElevenLabs

> Plataforma de síntese de voz com IA, capaz de clonar vozes e gerar narrações ultra-realistas.

---

## 🔗 Acesso

- **Site oficial:** [https://elevenlabs.io](https://elevenlabs.io)
- **API:** [https://api.elevenlabs.io/docs](https://api.elevenlabs.io/docs)
- **Plano gratuito:** 10.000 caracteres/mês

---

## 📋 O que é?

O **ElevenLabs** é a plataforma líder em geração de voz com IA, capaz de criar narrações naturais,
clonar vozes reais e gerar áudio em múltiplos idiomas. É a ferramenta ideal para criar
**podcasts, narração de vídeos, audiobooks e conteúdo de áudio** sobre qualquer tema.

---

## 🏋️ Como usar no contexto "Natty or Not"?

### 1. Narração de Podcast
Gere episódios de podcast completos com voz sintética profissional:

```
Texto de entrada:
"Bem-vindos ao episódio de hoje, onde vamos explorar um dos debates
mais acalorados do fisiculturismo: Natty or Not. O que separa um atleta
natural de um assistido? A ciência tem resposta para isso?..."

→ Saída: arquivo MP3 com narração realista em português
```

### 2. Roteiros de Vídeo (Voice-over)
Combine com ferramentas de vídeo como Runway ML e HeyGen:
```
1. ChatGPT → gera o roteiro
2. ElevenLabs → converte em narração
3. Runway ML → cria o vídeo
= Conteúdo completo sobre "Natty or Not" sem aparecer na câmera
```

### 3. Clonagem de Voz (Voice Cloning)
Com amostras de áudio, o ElevenLabs replica sua voz:
```python
import elevenlabs

# Clonar voz com amostras de áudio
voice = elevenlabs.clone(
    name="Minha Voz",
    description="Narrador fitness",
    files=["sample1.mp3", "sample2.mp3"]
)

# Gerar narração
audio = elevenlabs.generate(
    text="O fisiculturismo natural exige anos de dedicação...",
    voice=voice
)
```

### 4. Múltiplos Personagens para Debate
```
Personagem 1 (Atleta Natural) → Voz masculina grave
Personagem 2 (Especialista Médico) → Voz feminina séria
Personagem 3 (Moderador) → Voz neutra
= Podcast simulado de debate sobre "Natty or Not"
```

---

## ✅ Pontos Fortes

| Característica | Avaliação |
|---|---|
| Qualidade da voz | ⭐⭐⭐⭐⭐ — Ultra-realista |
| Idiomas | ⭐⭐⭐⭐⭐ — Incluindo português |
| Clonagem de voz | ⭐⭐⭐⭐⭐ — Poucos minutos de áudio |
| API | ⭐⭐⭐⭐⭐ — Bem documentada |
| Plano gratuito | ⭐⭐⭐⭐ — 10k chars/mês |

---

## ⚠️ Limitações

- Clonagem de voz de terceiros sem consentimento é **antiético e ilegal**
- Plano gratuito tem limite mensal de caracteres
- Voz em português pode ter sotaque leve em alguns modelos
- Conteúdo gerado deve respeitar os termos de uso (proibido deepfakes maliciosos)

---

## 💡 Fluxo Completo de Conteúdo

```
ChatGPT/Claude → roteiro do episódio
       ↓
ElevenLabs → narração em áudio (MP3)
       ↓
HeyGen/Runway → vídeo com avatar ou b-roll
       ↓
YouTube/Spotify → publicação do conteúdo
```

---

*← [Voltar ao README principal](../README.md)*
