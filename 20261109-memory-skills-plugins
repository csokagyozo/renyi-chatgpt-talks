# ChatGPT Memory, Skills, Plugins & Customization

## 1. ChatGPT's Five Memory Layers

ChatGPT uses several layers of memory and context, each operating at different scopes and persistence levels. This is a **conceptual classification**, not an official OpenAI architecture.

| Layer | Type | What it contains | Persistence |
|---|---|---|---|
| **L1 — Working memory** | Conversation context | Current messages, instructions, relevant tool outputs | Current conversation |
| **L2 — Episodic memory** | Chat history | Information retrieved from previous conversations | Across conversations, when enabled |
| **L3 — Semantic personal memory** | Long-term personalization | Preferences, background, goals, recurring interests | Persistent, automatically updated |
| **L4 — Project memory** | Scoped context | Project conversations, documents, and instructions | Persistent within a project |
| **L5 — External memory** | Connected knowledge | Files, connected apps, and external information sources | Available when authorized and accessible |

**Additional context sources:**
- **Parametric knowledge:** Knowledge encoded in the model's weights during training.
- **Application context:** Account metadata, session information, and system instructions supplied by the platform. Information visible in the UI is not necessarily available to the model.

## 2. Skills, Connected Apps & Plugins

These mechanisms extend ChatGPT beyond its general conversational capabilities.

| Component | Definition | Primary role |
|---|---|---|
| **Skill** | A reusable package of instructions, optional scripts, reference materials, and assets defining how to perform a task. | **Procedural knowledge:** How to perform specific tasks and workflows. |
| **Connected App** | An integration with external applications or services, enabling ChatGPT to retrieve information and execute supported operations through natural language. | **External access:** What external information and actions are available. |
| **Plugin** | An extension package that can combine Skills, Connected Apps, and other functionality into integrated capabilities. | **Capability packaging:** Combining and distributing reusable functionality. |

**How Skills work:** ChatGPT identifies relevant Skills using their metadata, loads their instructions (`SKILL.md`), and executes the workflow using additional resources or tools when necessary.

Skills are available in both conversational ChatGPT and Codex.

## 3. What Can Users Customize?

| Component | What is customizable? | How? |
|---|---|---|
| **Working memory (L1)** | Current conversation context | Messages, instructions, uploaded files |
| **Personal memory (L2–L3)** | Personal information, preferences, goals | Settings → Personalization → Memory |
| **Project memory (L4)** | Project context, instructions, documents | Create and configure Projects |
| **External knowledge (L5)** | Accessible external data and services | Connect applications and authorize access |
| **Custom Instructions** | Stable preferences and behavioral guidelines | Settings → Personalization |
| **Skills** | Task-specific procedures, workflows, templates | Create or install Skills via `/skills` |
| **Plugins** | Packaged capabilities and integrations | Install or configure through Plugins |
| **Model weights** | Not directly customizable in ChatGPT | Separate model training/fine-tuning services |

*L2 and L3 are conceptual distinctions and are not necessarily independently configurable.*

## 4. Key Architectural Distinctions

- **Memory:** What ChatGPT knows about the user and previous context.
- **Custom Instructions:** How ChatGPT should generally behave.
- **Skills:** How ChatGPT should perform particular tasks.
- **Projects:** Where related conversations, documents, and instructions are organized.
- **Connected Apps:** Which external systems ChatGPT can access.
- **Plugins:** How additional capabilities, including Skills and integrations, are packaged and distributed.

**Key takeaway:** ChatGPT combines conversational context, persistent knowledge, explicit instructions, procedural Skills, and external capabilities. These mechanisms differ in persistence, activation, and user control, but can work together to provide personalized and extensible AI functionality.
