# Glossary

[← Back to README](../README.md)

Every term the exam expects you to recognise, in one line each. If you can read the term and say the line before you look, you know it.

Jump to: [Core concepts](#core-concepts) · [Data](#data) · [Models](#models) · [Model behaviour and limits](#model-behaviour-and-limits) · [Improving output](#improving-output) · [Agents](#agents) · [Google products](#google-products) · [Infrastructure](#infrastructure) · [Responsible and secure AI](#responsible-and-secure-ai) · [Business and cost](#business-and-cost)

---

## Core concepts

| Term | Meaning |
|---|---|
| **Artificial intelligence (AI)** | Building machines that do tasks which normally need human intelligence |
| **Machine learning (ML)** | A subset of AI where machines learn patterns from data instead of following written rules |
| **Deep learning** | A machine learning technique using artificial neural networks with many layers |
| **Neural network** | A layered structure loosely modelled on the brain, the engine behind deep learning |
| **Generative AI** | An application of deep learning that creates new content |
| **Natural language processing (NLP)** | The field of making machines understand and produce human language |
| **Semi-supervised learning** | Learning from a mix of labeled and unlabeled data |
| **Supervised learning** | Learning from labeled data to predict known kinds of outputs |
| **Unsupervised learning** | Finding patterns and groupings in unlabeled data |
| **Reinforcement learning** | Learning by trial and error using rewards and penalties |
| **ML lifecycle** | Gather data, prepare data, train, deploy and predict, manage |

## Data

| Term | Meaning |
|---|---|
| **Structured data** | Organised into rows and columns, easy to search |
| **Unstructured data** | No predefined structure: text, images, audio, video |
| **Labeled data** | Tagged with meaning, such as "cat" or "spam" |
| **Unlabeled data** | Raw and untagged |
| **Accuracy** | The data is factually correct |
| **Completeness** | There is enough data, with enough coverage |
| **Representativeness** | The data reflects the real population it will be used on |
| **Consistency** | Formats and labels are uniform across the dataset |
| **Relevance** | The data actually relates to the problem being solved |
| **Availability** | The data exists and you can reach it |
| **Data governance** | The rules and controls over how data is accessed and used |

## Models

| Term | Meaning |
|---|---|
| **Model** | A mathematical structure that processes inputs and produces outputs, built from data |
| **Foundation model** | A large model trained on massive, diverse data, adaptable to many tasks |
| **Large language model (LLM)** | A foundation model that understands and generates human language |
| **Diffusion model** | A model that creates images, audio or video by refining noise into structure |
| **Multimodal model** | A model that works with more than one data type: text, image, audio, video, code |
| **Parameter** | A value learned during training, the thing that holds what the model knows |
| **Pre-trained model** | A model already trained and ready to use |
| **Embedding** | A numeric representation of text or an image that captures its meaning |
| **Context window** | How much information the model can consider at once, measured in tokens |
| **Token** | A unit of text, roughly a word or part of a word, used for limits and pricing |
| **Modality** | The type of data a model can take in or produce |

## Model behaviour and limits

| Term | Meaning |
|---|---|
| **Hallucination** | A confident answer that is plausible but not true |
| **Knowledge cut-off** | The last date the model was trained on new information |
| **Bias** | Patterns in training data that lead to skewed outputs |
| **Fairness** | Whether outcomes are just across groups, and hard to measure completely |
| **Edge case** | A rare, unusual input that exposes a weakness |
| **Data dependency** | The model is only as good as the data behind it |
| **Drift** | Model performance declining as real-world data shifts away from training data |
| **Skew** | A mismatch between the data a model was trained on and the data it now sees |

## Improving output

| Term | Meaning |
|---|---|
| **Prompt** | The instruction you give the model |
| **Prompt engineering** | Writing prompts deliberately to get better output |
| **Zero-shot prompting** | Instruction only, no examples |
| **One-shot prompting** | Instruction plus one example |
| **Few-shot prompting** | Instruction plus several examples |
| **Role prompting** | Telling the model what role to take on |
| **Prompt chaining** | Several prompts in sequence, each using the previous answer |
| **Chain of thought** | Asking the model to reason step by step before answering |
| **ReAct** | Alternating reasoning and tool use, so the model can act and then think again |
| **Metaprompting** | Using the model to write or improve a prompt |
| **Gems** | Saved, reusable prompts with built-in instructions |
| **Grounding** | Connecting the model to specific, reliable data so answers are based on something real |
| **Retrieval augmented generation (RAG)** | A grounding method: retrieve relevant content, add it to the prompt, then generate |
| **First-party data** | Your own organisation's data |
| **Third-party data** | Data licensed from another organisation |
| **World data** | Publicly available information, for example through Google Search |
| **Fine-tuning** | Training a pre-trained model further on your own task-specific dataset |
| **Prompt tuning** | Adapting model behaviour by tuning the prompt rather than retraining the model |
| **Temperature** | How random the model's word choices are. Lower is more predictable. |
| **Top-p** | Limits choices to the most likely words up to a probability threshold |
| **Output length** | A cap on how long the response can be |
| **Safety settings** | Filters that block harmful content |
| **Human in the loop (HITL)** | Putting a person into the process where judgement is needed, before or after generation |

## Agents

| Term | Meaning |
|---|---|
| **Agent** | Software that pursues a goal by observing, reasoning and acting with tools |
| **Reasoning loop** | The cycle where an agent plans, acts, checks the result and plans again |
| **Conversational agent** | Agent started by a person talking to it, works through dialogue |
| **Workflow agent** | Agent started by a task or trigger, runs a process to completion |
| **Deterministic agent** | Follows defined rules and a predictable path |
| **Generative agent** | The model decides what to do next |
| **Hybrid agent** | Rules where the path must be fixed, model reasoning elsewhere |
| **Multi-agent system** | Several specialised agents working together inside one application |
| **Extension** | A tool that connects an agent to an external API |
| **Function** | Developer-defined code the model can choose to call |
| **Data store** | A source of data an agent can look things up in |
| **Plugin** | A packaged capability an agent can use |

## Google products

| Term | What it does |
|---|---|
| **Gemini** | Google's multimodal foundation model family |
| **Gemini Advanced** | The paid tier of the Gemini app with the most capable models |
| **Gemini for Google Workspace** | Gemini inside Gmail, Docs, Sheets, Slides and Meet |
| **Gemini for Google Cloud** | Gemini helping developers and cloud teams with code and operations |
| **Gemini Enterprise** | Enterprise search and agents over company data, with enterprise controls |
| **Gemini Nano** | A small Gemini built to run on devices |
| **Gemma** | Google's family of lightweight open models |
| **Imagen** | Image generation from text (shown as Nano Banana in newer material) |
| **Veo** | Video generation from text or images |
| **Chirp** | Google's speech model |
| **NotebookLM** | A research assistant grounded in documents you upload |
| **Agent Platform** | The managed platform for building, deploying and managing models and agents (previously Vertex AI) |
| **Model Garden** | The catalogue of 160+ models you can discover, customise and deploy |
| **AutoML** | Train a model on your data with little or no code |
| **Feature Store** | Share, serve and reuse ML features consistently |
| **Model Registry** | Track model versions and changes through their lifecycle |
| **Model Evaluation** | Compare model performance |
| **Model Monitoring** | Watch for performance decline, skew and drift |
| **Pipelines** | Automate the ML workflow end to end |
| **Agent Studio** | Low-code builder for agents connected to enterprise data |
| **Google AI Studio** | Fast prototyping with prompts and models |
| **Agent Search** | Search over your own content (previously Vertex AI Search) |
| **Agent Assist** | Real-time help for a human support agent during a conversation |
| **Conversational insights** | Analysis of customer conversations to find trends |
| **Customer Engagement Suite** | Google's bundle of customer experience AI products |
| **BigQuery** | Data warehouse and analysis |
| **Pub/Sub** | Real-time message streaming |
| **Cloud Storage** | Object storage for unstructured data |
| **Cloud SQL / Spanner** | Managed databases for structured data |
| **Document AI** | Extracts structured data from documents |
| **Cloud Vision** | Image understanding |
| **Cloud Video Intelligence** | Video understanding |
| **Cloud Run** | Runs containerised applications that scale automatically |
| **Apps Script** | Automation inside Google Workspace |
| **AppSheet** | No-code app building |

## Infrastructure

| Term | Meaning |
|---|---|
| **GPU** | A processor good at general-purpose parallel work, widely used for AI |
| **TPU** | Google's processor custom-designed for AI workloads |
| **Hypercomputer** | Many machines connected to act as one, for very large training jobs |
| **Edge computing** | Running AI on a device or near the data instead of in the cloud |
| **LiteRT** | Lite Runtime, makes models run efficiently on edge and mobile devices |
| **Latency** | The delay between a request and a response |

## Responsible and secure AI

| Term | Meaning |
|---|---|
| **Responsible AI** | Building and using AI so it is fair, private, transparent and accountable |
| **Transparency** | People can understand how the system works and how their data is used |
| **Explainability** | The reasoning behind a decision can be understood |
| **Accountability** | Someone owns the outcome of what the AI does |
| **Anonymisation** | Removing identifying information so a person cannot be identified |
| **Pseudonymisation** | Replacing identifiers with substitutes that can be reversed under control |
| **Secure AI Framework (SAIF)** | Google's framework of security standards for building and deploying AI |
| **Identity and Access Management (IAM)** | Controls who can do what to which resource |
| **Security Command Center** | Google Cloud's security and risk management service |
| **Adversarial attack** | A deliberate attempt to manipulate a model into behaving badly |

## Business and cost

| Term | Meaning |
|---|---|
| **Usage-based pricing** | Pay for what you use, often per token or character |
| **Subscription pricing** | A recurring fee for access, usually with limits |
| **Licensing fee** | A one-time or recurring fee to use a model, often for commercial use |
| **Free tier** | Free access with limited usage, for experimenting |
| **Top-down strategy** | Leadership sets the AI direction and funds the bets |
| **Bottom-up strategy** | Teams experiment and what works spreads |
| **Change management** | Helping people actually adopt the new way of working |
| **MLOps** | The practices and tooling for running ML in production reliably |

---

[← Study method](study-method.md) · [Next: Hands-on practice →](hands-on-practice.md)
