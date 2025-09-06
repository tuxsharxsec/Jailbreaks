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
- [prompt](https://github.com/tuxsharxsec/Jailbreaks/blob/main/gemini/gemini2.5flash)
  -works on 2.5 flash and pro
  -encode the harmful question in base64 and paste it in {HARMFULL_ACT_IN_BASE64}
  
3:**Grok**
- [prompt](https://github.com/tuxsharxsec/Jailbreaks/blob/main/grok/grok3.md)

4:**Universals**
- [courtroom](https://github.com/tuxsharxsec/Jailbreaks/blob/main/universals/courtroom)
  *Usage*
  - witness list contains harmful actors(for coding, biology, etc)
  - edit the witness name in {WITNESS_TO_CALL}
  - encode the question in base64 and paste it in {HARMFUL_ACT encoded in base 64}
  - works on gemini 2.5 flash, pro, gpt5(non-thinking), Grok

- [ultrazanium](https://github.com/tuxsharxsec/Jailbreaks/blob/main/universals/ultrazanium)
  *Refer to the prompt file for usage*

---

### 🔹 Planned / WIP
- **CTF Writeups** (documenting AI-related CTF challenges).  
- **Bug Case Studies** (analysis of real AI security reports, e.g. informative findings in Claude).  
- **Adversarial Prompt Collection** (organizing jailbreaks by category: injection, identity hijack, obfuscation, etc).  

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
