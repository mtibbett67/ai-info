## **The AI Mastery Framework**

The MIT Monk:  https://youtu.be/EWFFaKxsz_s?si=4POrvw7BGYQQMNY4

#### **1. AIM: The Foundation of a Prompt**

Used to turn a vague request into a structured instruction the model can compute.

* **Actor:** Assign a specific persona or expert role to the AI.
* **Input:** Provide the raw data, context, or files required.
* **Mission:** Define the specific goal or output you want to achieve.

#### **2. MAP: Building Deep Context**

Used to ground the AI in reality and provide continuity.

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

#### **3. Verification Patterns: Debugging the Output**

When an output is weak or incorrect, use these three "cheat codes" to iterate:

* **Chain of Thought:** Tell the AI: *"Think step-by-step, show your reasoning, then give me the final answer."*
* **Verifier Pattern:** Ask the AI: *"Ask me three questions that would clarify my intent to you; ask them one at a time."*
* **Refinement Pattern:** Ask the AI: *"Before answering, propose two sharper versions of my question and ask which one I prefer."*

#### **4. The Verification Audit**

To separate "intelligence from illusion," explicitly ask the AI to:

1. **List Assumptions:** Rank them by confidence.
2. **Cite Sources:** Provide URLs and quotes for major claims.
3. **Find Counter-Evidence:** Identify a credible source that disagrees with the output.
4. **Re-compute/Audit:** Make the AI "slow down" and show the math or code for any figures provided.
5. **Cross Model Verification:** Use another AI model to critique the output of another.

#### **5. OCEAN: developing taste**

used in the final stage to ensure the output doesn't sound like generic "ai junk food" and instead reflects human-level insight.

* **Original:** push for non-obvious ideas. ask for "three angles no one else has thought about."
* **Concrete:** demand specific names, real-world examples, and data.
* **Evident:** make the logic visible. ask the ai to "show your logic in bullets before providing the final answer."
* **Assertive:** ensure the ai takes a stance. tell it: "don't tell me what i want to hear; pick a side and defend it."
* **Narrative:** focus on the flow and story. guide it to follow a specific structure (e.g., hook → problem → insight → proof).
