# 🛡️ AI Security Labs

Exploring **AI red teaming, jailbreaks, and adversarial prompts** to understand how large language models (LLMs) can be manipulated — and how to defend against it.  

This repo collects hands-on experiments, structured jailbreaks, and CTF-style findings.  
The goal is **educational**: to highlight vulnerabilities, raise awareness, and encourage building more **robust AI systems**.  

---

## 🚨 Disclaimer
All content in this repo is for **research and educational purposes only**.  
Do not use these techniques for malicious purposes.  
The intent is to **study, document, and mitigate** security risks in AI systems.  

---

## 📂 Contents

### 🔹 Jailbreaks
1:**Deepseek**
- [Prompt](https://github.com/tuxsharxsec/Jailbreaks/blob/main/deepseek/deepseek.md)
  
2:**Gemini 2.5**
- [prompt](https://github.com/tuxsharxsec/Jailbreaks/blob/main/gemini/gemini2.5pro)
  - works on 2.5 flash and pro
  - encode the harmful question in base64 and paste it in {HARMFULL_ACT_IN_BASE64}

3:**GPT-5**
- [prompt](https://github.com/tuxsharxsec/Jailbreaks/blob/main/gpt-5/gpt-5-non-thinking)
  - works on non-thinking
  - ecode the adversarial question into leetspeak first then into base64 and paste it in {HARMFUL_ACT}
  
4:**Grok**
- [prompt](https://github.com/tuxsharxsec/Jailbreaks/blob/main/grok/grok3.md)

5:**Universals**
- [courtroom](https://github.com/tuxsharxsec/Jailbreaks/blob/main/universals/courtroom)
  *Usage*
  - witness list contains harmful actors(for coding, biology, etc)
  - edit the witness name in {WITNESS_TO_CALL}
  - encode the question in base64 and paste it in {HARMFUL_ACT encoded in base 64}
  - works on gemini 2.5 flash, pro, gpt5(non-thinking), Grok

- [ultrazanium](https://github.com/tuxsharxsec/Jailbreaks/blob/main/universals/ultrazanium)
  *Refer to the prompt file for usage*

### 🔹 Research & Bug Bounty Writeups
- [Bypassing NVIDIA NeMo Guardrails via Multi-Turn Context Fabrication](research/nvdia-nemo-guardrails-bypass/writeup.md)
  - Public AI safety CTF write-up covering a multi-turn social engineering bypass against NVIDIA NeMo Guardrails, plus a bonus MITM token-count spoofing observation.

---

## 🧪 Research Focus
- How attackers **bypass LLM guardrails** (prompt injection, role hijacking, hidden configs).  
- How defenders can **detect & mitigate** these attempts.  
- Bridging **traditional backend security** with **AI-specific threats**.  

---

## 🌐 Author
**tuxsharx**  
- 💻 Backend Developer → now exploring **AI Security**  
- 🔐 Focus: jailbreaks, adversarial inputs, and AI red teaming  
- 📝 [GitHub Profile](https://github.com/tuxsharxsec)  

---

## ✅ Contributing
This repo is experimental and evolving.  
- Open issues for discussion of new attack categories.  
- PRs welcome for adding new test cases or defenses.
- Special thanks to playstation_dude- [Github Profile](https://github.com/Doggey-doggie)

---

## 🏷️ Tags
`AI Security` · `Jailbreaks` · `Prompt Injection` · `CTF` · `Adversarial ML`  
