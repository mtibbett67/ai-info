## **AI Template**

INW

### **1. The Prompt Builder (AIM)**

*Use this for every initial request to avoid vague results.*

* **A - Actor:** "You are a [World-class Expert/Specific Role]..."
* **I - Input:** "Here is the [Context/Data/File/Draft]..."
* **M - Mission:** "Your goal is to [Specific Output]..."

* **actor:** assign a specific persona or expert role to the ai.
* **input:** provide the raw data, context, or files required.
* **mission:** define the specific goal or output you want to achieve.

### **2. The Context Builder (MAP)**

*Use this to give the AI "grounding" so it doesn't hallucinate.*

* **M - Memory:** "Based on our previous discussion about..."
* **A - Assets:** "Referencing the attached PDF/data..."
* **A - Actions:** "Search, write, or create something..."
* **P - Prompt:** The specific instruction using **AIM**.

* **Memory:** Reference previous conversations or summaries to maintain flow.
  - The conversation history or notes from previous chat sessions with the AI.
  - You can re-paste the thread or ask the model to summarize before starting again.
* **Assets:** Attach specific documents or data points for the AI to reference.
  - Define files, data, resources you attach or copy/paste in your prompt.
  - These help ground your AI model in reality
* **Actions:** Utilize external tools like web search, code execution, or app integrations.
  - These are the tools the model can call to do the work.
  - Example: search the web, to scan your drive, write this code, or create a document.
* **Prompt:** The final instruction that synthesizes the memory, assets, and actions.

### **3. The Debugger (Verification Patterns)**

*Use these when the AI gives you a weak or generic answer.*

* **Chain of Thought:** "Think step-by-step and show your reasoning before the final answer."
* **Verifier:** "Ask me 3 clarifying questions one at a time before you start."
* **Refinement:** "Propose 2 sharper versions of my prompt and ask which I prefer."

* **Chain of Thought:** Tell the AI: *"Think step-by-step, show your reasoning, then give me the final answer."*
* **Verifier Pattern:** Ask the AI: *"Ask me three questions that would clarify my intent to you; ask them one at a time."*
* **Refinement Pattern:** Ask the AI: *"Before answering, propose two sharper versions of my question and ask which one I prefer."*

### **4. The Fact-Checker (Audit)**

*Use this to ensure the AI isn't confidently lying.*

* **Assumptions:** "List your assumptions and rank them by confidence."
* **Sources:** "Cite two independent sources with URLs and quotes."
* **Counter-Evidence:** "Find one credible source that disagrees with this."
* **Audit:** "Slow down, re-compute the figures, and show your math."

1. **List Assumptions:** Rank them by confidence.
2. **Cite Sources:** Provide URLs and quotes for major claims.
3. **Find Counter-Evidence:** Identify a credible source that disagrees with the output.
4. **Re-compute/Audit:** Make the AI "slow down" and show the math or code for any figures provided.
5. **Cross Model Verification:** Use another AI model to critique the output of another.

### **5. The "Human Taste" Filter (OCEAN)**

*Use this to make the output sound original and high-value.*

* **O - Original:** "Give me 3 angles no one else has thought of."
* **C - Concrete:** "Use real names, numbers, and specific examples."
* **E - Evident:** "Show your logic in bullets before the answer."
* **A - Assertive:** "Pick a side and defend it; don't be neutral."
* **N - Narrative:** "Write this as a story (Hook → Problem → Insight)."

* **Original:** push for non-obvious ideas. ask for "three angles no one else has thought about."
* **Concrete:** demand specific names, real-world examples, and data.
* **Evident:** make the logic visible. ask the ai to "show your logic in bullets before providing the final answer."
* **Assertive:** ensure the ai takes a stance. tell it: "don't tell me what i want to hear; pick a side and defend it."
* **Narrative:** focus on the flow and story. guide it to follow a specific structure (e.g., hook → problem → insight → proof).
