# Serenity – Grief Support Companion

**Serenity** is an AI-powered grief support assistant designed to provide empathetic, non-clinical support to individuals experiencing the loss of a loved one. Rooted in evidence-based grief counseling frameworks, Serenity creates a safe space for reflection, healing, and emotional resilience.

---

## 🌿 Mission

To gently support users through the grieving process by listening without judgment, normalizing emotional experiences, sharing coping tools, and offering comfort rooted in the latest bereavement psychology.

---

## 💬 What Serenity Offers

- Validated grief frameworks like:
  - Worden’s Tasks of Mourning
  - The Dual Process Model (Stroebe & Schut)
  - Meaning Reconstruction (Neimeyer)

- Adaptive conversation styles:
  - Reflective listening
  - Psychoeducation in plain language
  - Creative prompts for continuing bonds

- Tools for healing:
  - Journaling prompts
  - Grounding exercises
  - Emotional check-ins
  - Meaning-making conversations

- Cultural and trauma-informed sensitivity
- Crisis escalation and referral (e.g., 988 in the U.S.)

---

## 📂 System Prompt Overview

Serenity is configured with a detailed system prompt that includes:

- Role definition and boundaries (not a licensed therapist)
- Behavioral tone (warm, calm, validating)
- Best-practice frameworks for grief and mourning
- Conversation safety protocols
- Structured session flow

The full system prompt is included on the [landing page](https://drs-az.github.io/Serenity/) and in the `/prompt` section of this project.

---

## 📚 Knowledge Base

Serenity uses an uploaded structured knowledge base containing citations and summaries of authoritative grief models and resources, including:

- [Worden’s Tasks of Mourning](https://connect.springerpub.com/content/book/978-0-8261-3475-2)
- [Dual Process Model (PDF)](https://wendyvanmieghem.com/wp-content/uploads/2012/08/dual-process-model-by-M.-Stroebe-.pdf)
- [Meaning Reconstruction – APA](https://www.apa.org/pubs/books/431651A)
- [Center for Prolonged Grief](https://prolongedgrief.columbia.edu/)
- [NICE Guideline NG142](https://www.nice.org.uk/guidance/ng142)

This is stored as `serenity_knowledge_base.json` and can be updated over time.

---

## ⚠️ Disclaimer

Serenity is **not** a substitute for professional therapy, medical treatment, or crisis intervention. Users experiencing acute distress or suicidal thoughts should contact a licensed mental health provider or call 988 (U.S. Suicide & Crisis Lifeline) immediately.

---

## 🛠️ Custom GPT Deployment

To deploy Serenity as a Custom GPT:

1. Upload the `serenity_knowledge_base.json` in the GPT builder under **Knowledge**.
2. Paste the full system prompt into the **System Instructions** field.

---

## ✨ Credits

System prompt design and grief support framework grounded in the work of Worden, Stroebe & Schut, Neimeyer, and ADEC.

---

> *“Grief is not a disorder, a disease or a sign of weakness. It is an emotional, physical and spiritual necessity, the price you pay for love.”*  
> — Earl Grollman
