## Categorization of Prompt Patterns

### **Prompt Pattern Categories**

![Prompt Patterns Diagram](sandbox:/mnt/data/prompt_patterns_diagram.png)

---

### 📂 **Category 1: Instruction-Based Patterns**
👉 *Focus is on clear task instructions — direct or detailed*

| Pattern                     | Description                                      |
|----------------------------|--------------------------------------------------|
| **Instruction-Only**       | Plain task command without extra context         |
| **Constraint Prompting**   | Adds word/logic/format limits                    |
| **Output Format Prompting**| Specifies output like JSON, tables, etc.         |
| **Skeleton/Template Prompting** | Provides a blank structure to fill          |

---

### 📂 **Category 2: Contextual & Role-Driven Patterns**
👉 *Add persona, context, or background to influence the model's output*

| Pattern                       | Description                                 |
|------------------------------|---------------------------------------------|
| **Role Prompting**           | Assigns a role or persona                   |
| **Delimiter / Boundary Setting** | Explicit context boundaries             |
| **Reframing / Multi-Perspective** | Covers positive/negative or multi-angle |
| **Comparative / Hypothetical** | Asks for comparison or what-if scenarios  |

---

### 📂 **Category 3: Reasoning-Driven Patterns (Cognitive Control)**
👉 *Patterns that push the model to reason, think, or refine output*

| Pattern                          | Description                                 |
|----------------------------------|---------------------------------------------|
| **Chain of Thought (CoT)**       | Step-by-step reasoning                      |
| **Tree of Thought (ToT)**        | Multi-path reasoning trees                  |
| **Iterative / Reflective Prompting** | Self-review and improvement            |
| **Instruction Chaining**         | Break down complex tasks into steps         |

---

### 📂 **Category 4: Example-Driven Patterns**
👉 *Guide the model with examples or demonstrations*

| Pattern                          | Description                                 |
|----------------------------------|---------------------------------------------|
| **Few-Shot Prompting**           | Provide examples, ask for similar output    |
| **Zero-Shot Prompting**          | Direct task without examples                |
| **Multiple Choice / Option Prompting** | Provide options to pick from            |

---

### 📂 **Category 5: Advanced / Hybrid Patterns**
👉 *Combine reasoning, structure, and control — used in complex workflows*

| Pattern                          | Description                                 |
|----------------------------------|---------------------------------------------|
| **Retrieval-Augmented (RAG)**    | External knowledge injection                |
| **Multi-modal Prompting**        | Combine text, images, audio                  |
| **Debate / Self-Critique / Agent Prompting** | Force pros/cons or debates        |

---

### **Optional QA Testing Perspective:**
| Category                    | Best Fit For QA / Test Case Generation             |
|----------------------------|----------------------------------------------------|
| **Instruction-Based**      | API tests, simple test case writing             |
| **Contextual/Role-Based**  | Business rule-heavy scenarios                   |
| **Reasoning-Driven**       | Complex flows, edge cases, exploratory tests     |
| **Example-Driven**         | Ensuring consistent test case formats            |
| **Advanced**               | Test coverage validation, RAG for specs          |

---
