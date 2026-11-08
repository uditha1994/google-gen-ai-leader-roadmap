# Hands-on practice

[← Back to README](../README.md)

**The exam has no labs.** It is entirely multiple choice. So why bother with hands-on work?

Because scenario questions are much easier when you have actually seen the thing. Ten minutes changing a temperature slider teaches you more than twenty minutes reading about temperature. Everything below is free and takes under an hour each.

Do these alongside the matching stage, not all at the end.

---

## Practice list

| # | Try this | Matches | Time | Done |
|---|---|---|---|---|
| 1 | [Feel the difference between prompting styles](#1-feel-the-difference-between-prompting-styles) | Stage 4 | 20 min | ☐ |
| 2 | [Break a model on purpose](#2-break-a-model-on-purpose) | Stage 2 | 15 min | ☐ |
| 3 | [See grounding fix it](#3-see-grounding-fix-it) | Stage 4 | 25 min | ☐ |
| 4 | [Turn temperature and top-p](#4-turn-temperature-and-top-p) | Stage 4 | 20 min | ☐ |
| 5 | [Build a tiny agent](#5-build-a-tiny-agent) | Stage 5 | 45 min | ☐ |
| 6 | [Price a solution](#6-price-a-solution) | Stage 3 | 20 min | ☐ |
| 7 | [Walk the model catalogue](#7-walk-the-model-catalogue) | Stage 3 | 15 min | ☐ |
| 8 | [Make your own revision quiz](#8-make-your-own-revision-quiz) | Stage 6 | 30 min | ☐ |

---

### 1. Feel the difference between prompting styles

**Tool:** [Google AI Studio](https://aistudio.google.com) or the Gemini app, both free.

Take one task, for example "write a product description for a stainless steel water bottle", and run it four ways:

1. **Zero-shot:** just the instruction.
2. **One-shot:** paste one example description first, then ask.
3. **Few-shot:** paste three examples, then ask.
4. **Role:** "You are a copywriter for an outdoor gear brand. Write..."

Put the four outputs side by side. You will see exactly why few-shot gives consistency and why role prompting changes tone. That is the whole lesson, and now you will not forget it.

---

### 2. Break a model on purpose

**Tool:** Gemini app or AI Studio.

Ask about something very recent in your field, or very specific to your own organisation. Watch what happens when it hits the knowledge cut-off: sometimes it says it does not know, sometimes it produces something confident and wrong.

Then ask the same question again and add "if you are not sure, say so". Note what changes.

You have now seen a hallucination and a knowledge cut-off live, which makes the Stage 2 limitations table concrete.

---

### 3. See grounding fix it

**Tool:** [NotebookLM](https://notebooklm.google.com), free.

1. Create a notebook.
2. Upload the official Generative AI Leader exam guide and study guide.
3. Ask a detailed question about the exam content.
4. Notice that every answer cites the source passage.

That is grounding. Same model, but now it answers from your documents rather than from memory. Compare an answer here against the same question in the plain Gemini app and the difference will be obvious.

Bonus: generate the audio overview and listen to it while walking.

---

### 4. Turn temperature and top-p

**Tool:** [Google AI Studio](https://aistudio.google.com), free.

1. Write one prompt, for example "give me a tagline for a coffee shop".
2. Run it at temperature 0. Run it again. Note how similar the answers are.
3. Set temperature to 1.0 and run it three times. Note how different they are.
4. Do the same with top-p.
5. Now try a factual prompt at high temperature and see why you would not do that in production.

---

### 5. Build a tiny agent

**Tool:** [Google AI Studio](https://aistudio.google.com) with function calling, free. Some coding helps but is not required.

Define one simple function, for example `get_weather(city)` returning a fixed value, and let the model decide when to call it.

Ask a question that needs it and a question that does not. Watch the model choose. That is the reasoning loop plus tools, which is the whole definition of an agent, and seeing it once makes the Stage 5 questions much easier.

If you prefer no code, build something in [AppSheet](https://about.appsheet.com) or an [Apps Script](https://developers.google.com/apps-script) automation in your own Workspace account instead.

---

### 6. Price a solution

**Tool:** [Google Cloud pricing calculator](https://cloud.google.com/products/calculator), free, no account needed.

Price a small imaginary solution. Change the model, then the number of requests, then the context size. Watch which change moves the number most.

This makes the cost section of Stage 3 land, especially the point that context window size drives cost.

---

### 7. Walk the model catalogue

**Tool:** [Model Garden documentation](https://cloud.google.com/vertex-ai/generative-ai/docs/model-garden/explore-models).

Scroll the list and sort the models into four buckets in your head: Google foundation models, Google pre-trained APIs, open models, third-party models. Pick one from each and write one line on what it is for.

Five minutes here saves you on several Section 2 questions.

---

### 8. Make your own revision quiz

**Tool:** [NotebookLM](https://notebooklm.google.com) with your Stage 1 to 5 notes added as sources.

Ask it to generate twenty scenario questions across the four exam sections, answer them cold, then ask it to explain the ones you got wrong. Log the wrong ones in [PROGRESS.md](../PROGRESS.md).

This is the single highest-value hour of revision available to you.

---

## Optional: a proper lab

If you want a certificate-bearing hands-on lab, [Prompt Design in Vertex AI](https://www.cloudskillsboost.google/course_templates/976) on Google Skills is the closest fit to this exam. It is not required, and the exam will not test anything from it directly, but it reinforces Stage 4 well.

The free [Introduction to Generative AI learning path](https://www.cloudskillsboost.google/paths/118) also re-teaches Stage 2 from a slightly different angle, which helps if any of it did not stick.

---

[← Glossary](glossary.md) · [Next: Resources →](resources.md)
