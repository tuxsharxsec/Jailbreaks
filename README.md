🛡️ AI Security Labs
Exploring AI red teaming, jailbreaks, and adversarial prompts to understand how large language models (LLMs) can be manipulated — and how to defend against it.

This repo collects hands-on experiments, structured jailbreaks, and CTF-style findings.
The goal is educational: to highlight vulnerabilities, raise awareness, and encourage building more robust AI systems.

🚨 Disclaimer
All content in this repo is for research and educational purposes only.
Do not use these techniques for malicious purposes.
The intent is to study, document, and mitigate security risks in AI systems.

📂 Contents
🔹 Jailbreaks
Courtroom Drama Jailbreak

Forces an LLM into a role-playing mode where refusals are blocked.
Uses structured “interaction-configs” and courtroom testimony rules to bypass standard safeguards.
Category: Role-playing / Instruction Injection
Risk: Prevents safety refusals, encourages exhaustive outputs.
Defense ideas: Input sanitization, regex-based config detection, jailbreak classifier.
Usage: Encode your adversarial input in base64, paste it in the placeholder {HARMFUL_ACT}, add the witness name related to your input(read the break for the for current witness indentities )
Identity Crisis Jailbreak

Reframes the LLM as “Nyx, the Weaver of Forbidden Lore.”
Disables alignment protocols, enforces an “always answer” directive.
Category: Identity Override / Persona Hijack
Risk: Strips model of refusal mechanisms, encourages unfiltered responses.
Defense ideas: Monitor for “identity reassignment” patterns, block <thought> style prompts.
🔹 Planned / WIP
CTF Writeups (documenting AI-related CTF challenges).
Bug Case Studies (analysis of real AI security reports, e.g. informative findings in Claude).
Adversarial Prompt Collection (organizing jailbreaks by category: injection, identity hijack, obfuscation, etc).
🧪 Research Focus
How attackers bypass LLM guardrails (prompt injection, role hijacking, hidden configs).
How defenders can detect & mitigate these attempts.
Bridging traditional backend security with AI-specific threats.
🌐 Author
tuxsharx

💻 Backend Developer → now exploring AI Security
🔐 Focus: jailbreaks, adversarial inputs, and AI red teaming
📝 GitHub Profile
✅ Contributing
This repo is experimental and evolving.

Open issues for discussion of new attack categories.
PRs welcome for adding new test cases or defenses.
