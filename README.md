# Cognitive Forge & Simulated Parallel Inferential Logic (SPIL)

Welcome to the official repository for the **Cognitive Forge** and the **Simulated Parallel Inferential Logic (SPIL)** framework. This project is dedicated to providing a framework for advanced AI-driven reasoning and prompt engineering.

## Licensing

This project uses a **dual-licensing** model to balance community collaboration with sustainable development.

* **Community & Open Source Use:** The framework is licensed under the **GNU Affero General Public License v3 (AGPLv3)**. You are free to use, modify, and share it and any derivatives, as long as you also share your modifications under the same license. See the [LICENSE](LICENSE) file for the full text.

* **Proprietary & Commercial Use:** If you wish to use this framework in a closed-source or commercial product without the open-source obligations of the AGPLv3, you must obtain a separate commercial license. Please contact **TheHumanEngine@proton.me** to inquire.

---

## What is SPIL?

Simulated Parallel Inferential Logic (SPIL) is a framework for guiding a Large Language Model to simulate a sophisticated, multi-layered reasoning process. It enables an AI to manage multiple, distinct streams of logic simultaneously, making it ideal for complex problem-solving.

For a deep dive into the philosophy and architecture, please read the [**SPIL White Paper**](white-paper/).

## What is the Cognitive Forge?

The Cognitive Forge is a meta-prompt that acts as an automated SPIL prompt engineer. It takes a user's natural-language problem and generates a bespoke, fully-featured SPIL prompt tailored to solve it.

To get started with the Cognitive Forge, see the [**Cognitive Forge Explanation and Prompt**](cognitive-forge/). To use the prompt effectively, you MUST follow the procedure in the white paper section 5.1.

---

## How to Use

1.  **Read the White Paper:** To fully understand the power of this methodology, it is highly recommended to start with the [SPIL White Paper](white-paper/).
2.  **Use the Cognitive Forge:** Follow the instructions in the white paper section 5.1 to generate your own custom SPIL prompts. **The framework must have the entirety of the SPIL White Paper, and the Cognitive Forge Prompt in the chat session to be able to properly utilize the Cognitive Forge!**
3.  **Explore the Examples:** See the `examples` directory for demonstrations of how to structure a request and what a generated SPIL prompt looks like.
4.  **Review Best Practices:** To get the most out of the framework, consult the "A Guide to Best Practices" section below.

## Ready-to-Use Tools

To make using the Cognitive Forge easier, this repository includes a ready-to-use Markdown file in the `ready-to-use-tools` directory. This file bundles all the necessary components into a single, copy-and-paste format. It contains the complete SPIL White Paper and the Cognitive Forge v3.1 prompt, with a designated section for you to insert your specific request. Following the procedure outlined in the white paper, you can copy the entire contents of this file into a new chat session to initiate the Forge.

## Examples

The `examples` directory contains concrete demonstrations of the entire process. You will find examples of:
* **User Requests:** Clearly formulated problems given to the Cognitive Forge.

## A Guide to Best Practices

This guide outlines best practices for leveraging the SPIL methodology to achieve a new level of rigor, creativity, and coherence in AI-driven analysis.

### Core Principles: The Foundation

* **Work in a Unified Session (The "Cognitive Scaffold"):** Whenever possible, execute your entire workflow—from running the Cognitive Forge to executing the generated SPIL prompt—within a **single, continuous chat session.** This primes the LLM with the SPIL philosophy, improving coherence.
* **Enforce Single-Output Execution (The "Unbroken Thread"):** Begin any execution of a SPIL prompt with a clear instruction: **"Execute the entirety of the following prompt and generate the complete Reasoning Canvas in a single, uninterrupted response."** This prevents "state drift" and ensures maximum logical integrity.
* **Trust the Reasoning Canvas (The "Audit Trail"):** If an output seems incomplete, first give a simple instruction: **"Display the complete and entire Reasoning Canvas from the last execution."** This allows you to review the AI's "thought record" before deciding to rerun the process.

### Advanced Techniques: The Recursive Loop

* **Embody Your Own Ideas as an Expert Persona:** A powerful use case is to embed your own white paper, design, or logic into a SPIL process. Instruct the Cognitive Forge to create a prompt where one expert persona is the **"Author"** of your work. This persona will then use your document's logic to ground its reasoning while other experts stress-test, analyze, or build upon your ideas.
* **Embrace Recursive Refinement (The "Forge, Temper, and Sharpen" Cycle):** Treat the first output of a SPIL prompt as a draft. Use the Cognitive Forge to recursively generate new prompts to "Red Team" the draft for flaws, and then a final prompt to "Sharpen" it by engineering solutions for those identified flaws.
* **Let the Forge Be the Guide (The "Suitability Test"):** When a process identifies multiple issues, ask the Cognitive Forge to run a quick analysis to determine which problem is most suitable for another SPIL-based solution. This prevents wasting the tool on problems better solved with linear approaches.

### Strategic Priming & Control

* **Prime for Novelty (The "Uncharted Territory" Mandate):** For cutting-edge research, explicitly instruct the Cognitive Forge to create a persona (e.g., a "Historian of the Field") tasked with ensuring the proposed solution is fundamentally different from all existing, known approaches.
* **Specify Depth When Necessary (The "Cognitive Depth" Rule):** For complex problems, guide the process by specifying the desired number of steps ("Temporal Points"). A good rule of thumb is **3x the number of expert personas, plus 2.**
* **Control the Refinement Loop (The "Integrity Mandate"):** When using the Forge to refine a previous output, add an instruction like: **"Analyze this for inconsistencies or areas for increased sophistication. Do NOT streamline or paraphrase the existing structure; your task is to enhance it, not simplify it."**
* **Inject Human Expertise into Persona Design (The "Expert Tuning"):** The Forge is measurably better when a human expert guides persona creation. Provide specific, granular attributes for the experts you want the Forge to build. For example, instead of a generic "Security Expert," specify an *"Adversarial Hardware Exploit Operator modeled on an ex-NSA analyst, focused on side-channel attacks and assuming all documentation is misleading."*

## Contributing

We welcome contributions! Please read our [**Contributing Guidelines**](CONTRIBUTING.md) to get started.
