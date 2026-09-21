## 📌 About the Project

**WasteWise AI** is a conversational AI assistant that helps Indian urban households correctly identify, segregate, and dispose of household waste in real time.

India generates **62 million tonnes** of municipal solid waste every year — and over **80% ends up in landfills** due to improper segregation. WasteWise AI solves this by giving every household an always-available, multilingual waste advisor right in their browser.

Built as part of the **1M1B AI for Sustainability Virtual Internship** in collaboration with **IBM SkillsBuild & AICTE (July–September 2026)**.

---

## ✨ Features

- 🤖 **Real AI responses** — powered by Claude (Anthropic API)
- 🗑️ **4 waste categories** — Wet, Dry, Hazardous, E-Waste with color-coded bin badges
- 📋 **Step-by-step disposal instructions** for every item
- 🌱 **Eco sustainability tip** with every response
- 🌐 **Bilingual** — works in both Hindi and English
- ⚡ **Quick-tap suggestion chips** for common waste items
- 📱 **Mobile responsive** — works on all screen sizes

---

## 🎯 SDG Alignment

| SDG | Goal | How This Project Contributes |
|-----|------|------------------------------|
| **SDG 11** | Sustainable Cities & Communities | Reduces landfill burden in urban areas through better waste segregation |
| **SDG 12** | Responsible Consumption & Production | Promotes recycling, reuse, and responsible disposal habits |

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML / CSS / JavaScript | Frontend (single file, no framework) |
| Anthropic Claude API | AI waste classification and advisory |
| Prompt Engineering | Structured AI response formatting |
| GitHub Pages / Netlify | Free hosting and deployment |

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/wastewise-ai.git
   cd wastewise-ai
   ```

2. **Add your API key**

   Open `index.html` in a text editor and find the `headers:` block inside the `fetch()` call. Add your Anthropic API key:
   ```js
   headers: {
     'Content-Type': 'application/json',
     'x-api-key': 'YOUR_ANTHROPIC_API_KEY',
     'anthropic-version': '2023-06-01'
   }
   ```
   Get a free key at [console.anthropic.com](https://console.anthropic.com)

3. **Open the file**

   Simply open `index.html` in any browser — no server or installation needed.

---

## 📁 Project Structure

```
wastewise-ai/
│
├── index.html        # Main application (entire project in one file)
└── README.md         # Project documentation
```

---

## 💡 How It Works

```
User types a waste item (text)
        ↓
Claude AI classifies it:
WET | DRY | HAZARDOUS | E-WASTE
        ↓
Returns:
✅ Bin category + color badge
📋 Step-by-step disposal steps
🌱 One sustainability eco-tip
```

---

## 🌍 Expected Impact

- **15–20%** reduction in mixed waste from participating households
- **330,000+** households segregating correctly (10% of Delhi alone)
- Improved safety for sanitation workers
- Higher recycling rates → circular economy benefits
- Estimated **₹40 Cr+** saved annually in landfill processing costs

---

## ⚖️ Responsible AI

| Principle | Implementation |
|-----------|---------------|
| **Fairness** | Multilingual (Hindi + English), works for all income groups |
| **Transparency** | Every classification includes a reason why |
| **Ethics** | Only legal, official disposal routes recommended |
| **Privacy** | No personal data collected or stored |

---

## 👩‍💻 Built By

**[AARAV SINGH]**
[KCC Institute Of Technology and Management] · Greater Noida, Uttar Pradesh, India
1M1B AI for Sustainability Virtual Internship — July–September 2026
In collaboration with IBM SkillsBuild & AICTE

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> *"AI can be a force for sustainability, inclusion, and positive change."*
> — 1M1B Internship Guideline
