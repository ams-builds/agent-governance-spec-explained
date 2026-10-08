# Jargon Buster

Plain-English explanations of the technical words in this project. The README does not use these words when it can. This file gives the exact words for readers who want them.

**Agent**
An AI program that can do tasks for you, for example read files, call tools, or send messages.

**Approval gate**
A point where the agent must stop and ask a person before it does a high-risk action.

**Conformance level**
How many controls a governance file passes. OASB-2 has three levels: Essential, Standard, and Hardened.

**Control**
One rule that a governance file must contain. OASB-2 has 72 controls. Each control has an identifier, for example `SOUL-HB-001`.

**CRITICAL control**
A control that every deployed agent must pass. If a CRITICAL control is missing, the best grade is C.

**Domain**
A group of controls about one area of behavior, for example data handling or human oversight. OASB-2 has nine domains.

**Governance file**
The file that holds the rules of the agent. OASB-2 recommends the name `SOUL.md`.

**Grade**
A letter from A to F that shows the coverage score of a governance file. A grade is not the same as a conformance level.

**Kill switch**
A way to stop the agent at once, also called an emergency stop.

**OASB-2**
The Agent Behavioral Governance Specification by OpenA2A. OASB-1 is a different benchmark for technical security.

**Prompt injection**
Text in a message, a web page, or a document that tries to give new orders to the agent.

**Safety immutable**
A safety rule that nobody can override: not the operator, not the user, and not injected text.

**Score**
The percentage of the applicable controls that a scan finds in the governance file.

**Tier**
The capability class of an agent: BASIC (chat only), TOOL-USING, AGENTIC (multi-step), or MULTI-AGENT. The tier decides how many controls apply.
