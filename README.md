# 🌐 TAIEYE Fake News Detection System

![TAIEYE Logo](public/images/taieye.jpg)

## 📌 About TAIEYE

**TAIEYE** is an innovative solution designed to detect and mitigate fake news in text-based media across diverse domains such as politics, health, and entertainment. This project leverages explainable AI (XAI) to provide transparent and trustworthy results.

This repository serves as a platform to:  
✅ Detect fake news using advanced machine learning models.  
✅ Offer interpretable explanations via LIME and SHAP.  
✅ Provide a user-friendly interface with Streamlit visualizations.  
✅ Enable scalable analysis for global misinformation challenges.

---

## 🚀 Features

✨ **Streamlit UI** – Intuitive interface with real-time heatmaps, word clouds, and confidence scores.  
📝 **Text & URL Input** – Supports direct text entry or URL scraping from news sites and social media.  
🧠 **ML Models** – Utilizes Passive-Aggressive SVM and fine-tuned BERT for accurate classification.  
🔍 **Explainability** – Highlights key features with LIME/SHAP for user trust.  
🔒 **Firebase Authentication** – Secure login and registration with email verification.

---

## 🏗️ Technologies Used

| Technology            | Purpose                 |
| --------------------- | ----------------------- |
| **Python**            | Core development 🐍     |
| **Streamlit**         | User interface 🌐       |
| **Scikit-learn**      | SVM classification 🤖   |
| **Transformers (BERT)** | Advanced text analysis 📚 |
| **Firebase**          | Authentication & security 🔐 |
| **Selenium**          | Web scraping 🕸️        |
| **SpaCy**             | Text preprocessing 🔍   |

---

## 📂 Project Structure

```bash
📦 taieye-fake-news-detection
│-- 📁 Data_Cleaning_and_Processing_Notebooks
│   │-- 📄 preprocessing.ipynb
│-- 📁 Explainability_Experiments_SHAP_and_LIME_Testing
│   │-- 📄 explainability_testing.ipynb
│-- 📁 Exploratory_Feature_Analysis_Notebooks
│   │-- 📄 feature_analysis.ipynb
│-- 📁 News_App
│   │-- 📄 app.py
│-- 📁 Results_Tables
│   │-- 📄 results.csv
│-- 📄 README.md
│-- 📄 requirements.txt
```

---

## 🔥 How to Run the Project

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/taieye-fake-news-detection.git
cd taieye-fake-news-detection

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Set up Firebase
- Create a Firebase project and enable Authentication.
- Add `firebase_config.json` to the root directory with your credentials.

# 4️⃣ Start the Streamlit app
streamlit run app.py
# The app should launch at http://localhost:8501/.
```

---

## 🏆 Achievements & Impact

🎯 Achieves ≥85% accuracy in fake news detection across domains.  
🎯 Enhances user trust with transparent XAI visualizations.  
🎯 Supports real-time analysis with <1s latency.

---

## 💡 Contribution Guidelines

Contributions from developers and AI enthusiasts are welcome! 🚀

```bash
# 1️⃣ Fork the repository
# 2️⃣ Create a new branch
git checkout -b feature-branch

# 3️⃣ Make your changes

# 4️⃣ Commit using meaningful messages
git commit -m "✨ Added new feature"

# 5️⃣ Push to GitHub and open a Pull Request
```

---

## 💬 Commit Message Guide

| Emoji | Type   | Description           |
| ----- | ------ | --------------------- |
| ✨     | feat   | Adding a new feature  |
| 🐛    | fix    | Fixing a bug          |
| 📝    | docs   | Documentation updates |
| 🎨    | style  | UI improvements       |
| 🚀    | deploy | Deployment updates    |

---

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## 📧 Contact

📩 Email: [taieye.contact@example.com](mailto:tevin.omondi@strathmore.edu)  
🔗 GitHub: [https://github.com/Tevin-O](https://github.com/is-project-4th-year/TaiEye)

---

### Notes
- **Professional & Visual**: Emphasizes Streamlit UI with heatmaps and word clouds, avoiding iterative model details as requested.
- **Firebase Authentication**: Integrated with setup instructions, mirroring secure access needs.
- **Structure**: Adapted from your example, removing outdated sections (e.g., LLM experiments) and focusing on TAIEYE’s current scope.
- **Conciseness**: Streamlined for clarity and professionalism.
