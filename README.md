# ♻️ WasteWise AI

**A conversational AI assistant that helps Indian urban households correctly identify, segregate, and dispose of household waste, in real time.**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![HTML](https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JS-orange)
![SDG 11](https://img.shields.io/badge/SDG-11-f89d2a)
![SDG 12](https://img.shields.io/badge/SDG-12-bf8b2e)

---

## 📌 About the Project

India generates **62 million tonnes** of municipal solid waste every year, and over **80% of it ends up in landfills** because it isn't segregated properly at the source.

WasteWise AI tackles this by giving every household an always-available, bilingual (Hindi + English) waste advisor right in the browser. Type in any household item and get an instant answer on which bin it belongs in, how to dispose of it, and a small tip to reduce waste.

> Built as part of the **1M1B AI for Sustainability Virtual Internship**, in collaboration with **IBM SkillsBuild & AICTE** (July–September 2026).

---

## ✨ Features

- 🤖 **Real AI responses**: powered by Claude via the Anthropic API
- 🗑️ **4 waste categories**: Wet, Dry, Hazardous, and E-Waste, each with a color-coded bin badge
- 📋 **Step-by-step disposal instructions** for every item
- 🌱 **Eco sustainability tip** with every response
- 🌐 **Bilingual**: works in both Hindi and English
- ⚡ **Quick-tap suggestion chips** for common waste items
- 📱 **Mobile responsive**: works on all screen sizes
- 🪶 **Zero dependencies**: the whole app is a single HTML file, no build step

---

## 💡 How It Works

```
User types a waste item (Hindi or English)
              ↓
Claude classifies it:
WET | DRY | HAZARDOUS | E-WASTE
              ↓
Returns:
✅ Bin category + color badge
📋 Step-by-step disposal steps
🌱 One sustainability eco-tip
💬 A short reason for the classification
```

---

## 🛠️ Tech Stack

| Technology | Usage |
| --- | --- |
| HTML / CSS / JavaScript | Frontend (single file, no framework) |
| Anthropic Claude API | AI waste classification and advisory |
| Prompt Engineering | Structured AI response formatting |
| GitHub Pages / Netlify | Free hosting and deployment |

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- An Anthropic API key. You can get one at [console.anthropic.com](https://console.anthropic.com)

### Run Locally

1. **Clone the repository**

   ```bash
   git clone https://github.com/AaravSingh23/WASTeWISeAI.git
   cd WASTeWISeAI
   ```

2. **Add your API key**

   Open `index.html` in a text editor, find the `headers:` block inside the `fetch()` call, and add your key:

   ```js
   headers: {
     'Content-Type': 'application/json',
     'x-api-key': 'YOUR_ANTHROPIC_API_KEY',
     'anthropic-version': '2023-06-01'
   }
   ```

3. **Open the app**

   Double-click `index.html`, or open it in any browser. No server or installation needed.

### ⚠️ Security Note

Anything placed in front-end code is visible to anyone who opens the page. **Never commit your real API key to GitHub**, and don't deploy a public site with a real key embedded in `index.html`.

For a public deployment, route requests through a small backend or serverless function (for example, a Netlify Function) that stores the key as an environment variable.

---

## 📁 Project Structure

```
WASTeWISeAI/
│
├── index.html      # Main application (entire project in one file)
├── README.md       # Project documentation
├── LICENSE         # MIT License
└── .gitignore      # Git ignore rules
```

---

## 🎯 SDG Alignment

| SDG | Goal | How This Project Contributes |
| --- | --- | --- |
| **SDG 11** | Sustainable Cities & Communities | Reduces landfill burden in urban areas through better waste segregation |
| **SDG 12** | Responsible Consumption & Production | Promotes recycling, reuse, and responsible disposal habits |

---

## 🌍 Expected Impact

- **15–20%** reduction in mixed waste from participating households
- **330,000+** households segregating correctly (10% of Delhi alone)
- Improved safety for sanitation workers
- Higher recycling rates, supporting a circular economy
- An estimated **₹40 Cr+** saved annually in landfill processing costs

---

## ⚖️ Responsible AI

| Principle | Implementation |
| --- | --- |
| **Fairness** | Multilingual (Hindi + English), works for all income groups |
| **Transparency** | Every classification includes a reason why |
| **Ethics** | Only legal, official disposal routes are recommended |
| **Privacy** | No personal data collected or stored |

---

## 🗺️ Roadmap

- [ ] Backend proxy so the API key is never exposed in the browser
- [ ] Photo-based waste identification
- [ ] Support for more Indian regional languages
- [ ] City-specific disposal rules and nearby collection points

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to open an issue or submit a pull request.

1. Fork the project
2. Create your branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 👨‍💻 Built By

**Aarav Singh**
KCC Institute of Technology and Management · Greater Noida, Uttar Pradesh, India
1M1B AI for Sustainability Virtual Internship, July–September 2026
In collaboration with IBM SkillsBuild & AICTE

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> *"AI can be a force for sustainability, inclusion, and positive change."* — 1M1B Internship Guideline
