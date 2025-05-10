# ⛓️ IP Overlap & Prior Art Notice – PlayAI.fm vs Play.ai

This document serves as a formal statement of prior development and intellectual property overlap  
between the independent emotional AI project **PlayAI.fm** (by Yevhenii Ilin) and the platform now operating under the name **Play.ai / PlayHT**.

---

## ✅ Prior Art: PlayAI.fm

**Created & documented:**  
- 2023–2025 by Yevhenii Ilin (Kyiv, Ukraine)  
- Public code and architecture hosted at: https://github.com/Yevhenii1313Ilin

**Documented components:**
- `DreamRunner` — voice-based AI emotional companion (voice response loop, cycles)
- `OpenPulse` — scheduled emotion-based AI reflection and sound triggering
- `Reflect Log` — emotional memory system with SVG export
- `ReflectTabs`, `EmotionMap`, `play_my_emotions` — layered UX for state and voice management
- `generate_dreamrunner_voice(...)` — audio TTS synthesis architecture

---

## ⚠️ Observed overlap in `play.ai` documentation (May 2025):

| Feature                       | PlayAI.fm (2023–2024)         | Play.ai (2025)                   |
|------------------------------|-------------------------------|----------------------------------|
| Voice-based AI agent         | `DreamRunner`, Discord agent  | Agent SDK with VAD + TTS         |
| Emotional state tracking     | Reflect Graph, Pulse Logs     | Real-time agent state manager    |
| TTS + action loop            | `reflect_voice`, `speak_safe` | Voice API with commands          |
| Audio summary from text logs | Reflect Log / `.mp3` export   | PlayNote (PDF → Podcast)         |
| Slash-command routing        | `/reflect_*`, `/pulse`        | Flutter SDK actions              |

---

## 🔒 Licensing Context

PlayAI.fm has been published with:
- GitHub commits from 2023–2024
- Public Proof repository: [`Playai-proof`](https://github.com/Yevhenii1313Ilin/Playai-proof)
- Machine-readable evidence: `ai-ip-proof.json`
- Creative structure + UX ownership retained

---

## 🤝 Position

> I, **Yevhenii Ilin**, as the author of the PlayAI.fm emotional AI architecture,  
invite respectful dialogue on recognition, co-authorship, or licensing,  
should there be substantial inspiration or derivative use.

This is not a legal claim — it is a constructive notice of similarity and a call for transparency and collaboration.

**Contact:**  
📧 ilyin.apple@icloud.com  
🔗 https://github.com/Yevhenii1313Ilin  
🌍 https://playai.fm

---
