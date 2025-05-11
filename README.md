# 🤖 Prompty-Friendly-Helper

This project demonstrates how to use Microsoft's [Prompty](https://aka.ms/prompty) to build context-aware, personalized AI responses. Built as a Developer Advocate submission for **VickyBytes**.

---

## 🎯 Purpose

This repository includes a simple `.prompty` file and a sample output that demonstrates:

* User-defined inputs (`firstName`, `context`, `question`)
* A grounded system prompt
* Friendly, markdown-based responses

---

## 📁 Files Included

| File               | Description                                     |
| ------------------ | ----------------------------------------------- |
| `basic2.prompty`   | The main Prompty configuration file             |
| `Sample_output.md` | A sample output generated using the prompt file |

---

## 🎥 Demo Video

▶️ [Click here to watch the demo on Google Drive](https://drive.google.com/file/d/1DrL8GXjg4ZqlTmy-tOLbd7SIrjpK2st0/view?usp=sharing)

---

## 🧠 Prompt Logic

This prompt is designed to:

* Address the user by name
* Use context to ground the assistant's response
* Be brief, helpful, and human-friendly (with emojis!)

### Example Input

```yaml
firstName: Seth
context: >
  The Alpine Explorer Tent boasts a detachable divider, mesh windows, vents, waterproof design, and a gear loft.
question: What can you tell me about your tents?
```

### Example Output
```yaml
Hi Seth! 🏕️

The Alpine Explorer Tent is perfect for nature lovers. With mesh windows, a waterproof build...
```
## ⚙️ Technologies

- [Prompty](https://aka.ms/prompty) by Microsoft  
- Azure OpenAI / OpenAI Chat API  
- Markdown output rendering  

## 🙋‍♂️ Author
**Chirag Gupta**  
DevSec & Cloud Enthusiast 🌩️  
[GitHub](https://github.com/chirag1689) | [LinkedIn](https://www.linkedin.com/in/chirag-gupta-20640b24a/)

