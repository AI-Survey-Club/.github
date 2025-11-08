# SurveyAI

---

## 🧠 Overview

**SurveyAI** is an experimental AI-driven automation system that intelligently completes and interacts with surveys.  
---

## ⚙️ Core Features

- **🧭 Automated Navigation**  
  Dynamically moves through multi-page surveys with element detection and adaptive timing.

- **🗣️ Intelligent Q&A Processing**  
  Uses AI models to interpret question intent and generate appropriate, context-aware answers.

- **🧩 Annotation Layer**  
  Includes *Annotorious* integration for live annotation and visual debugging of automation paths.

- **🎛️ Configurable Survey Types**  
  Modular configuration system supporting Qualtrics, Google Forms, and other structured survey frameworks.

- **⚡ Real-time Interaction**  
  Uses Selenium, xdotool, and low-level event simulation for responsive interactions.

---

## 🚀 Usage

1. **Configure the environment:**
   - Update `config.json` with survey parameters.  
   - Populate `.env` with environment variables and credentials.

2. **Run the bot:**
   ```python
   python main.py
    ```

3. **Monitor logs:**

   * Output is streamed in real time for debugging and performance analysis.

---

## 🧩 Architecture

| Component                | Description                                             |
| ------------------------ | ------------------------------------------------------- |
| **AI Engine**            | Handles NLP-based understanding of survey questions     |
| **Automation Layer**     | Selenium-driven navigation and element management       |
| **Config System**        | JSON-based modular setup for survey type mapping        |
| **Annotation Interface** | Visual overlay for debugging or training feedback loops |

---

## 📜 License

Licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for details.

---

## 💬 Contact

* Discord: [Join the community](https://discord.gg/yMMyxDZuSS)
* GitHub: [GrimDevelopment](https://github.com/GrimDevelopment)
* Maintainer: [@0x7C2f](https://github.com/0x7C2f)

---

<p align="center">
  <sub><i>a GrimDevelopment project</i></sub>
</p>
