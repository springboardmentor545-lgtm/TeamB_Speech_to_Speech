# TeamB_Speech_to_Speech

# 🌍 AI Powered Real-Time Speech Translation for Multilingual Content

## 🔎 Project Description
This project focuses on building a **real-time speech-to-speech translation system** that transforms live commentary or spoken content from **English and Hindi** into more than **twelve languages**.  

The core idea is to integrate this solution seamlessly within **OTT digital platforms**, ensuring that users can enjoy live content in their **preferred language without any noticeable delay**.  

By leveraging **Azure OpenAI** and **Azure Speech-to-Text services**, the project aims to deliver **accurate translations with minimal latency**. The result is an **inclusive, accessible media experience** that can cater to global audiences across diverse linguistic backgrounds.  

---

## ⚙️ Tech Stack
- 🎙 **Azure Speech-to-Text** for real-time audio recognition  
- 🌍 **Azure OpenAI Services** for advanced natural language processing and translation  
- 🐍 **Python** for implementing scripts, data preprocessing, and model handling  
- 🖥 **VS Code** for experimentation, testing, and iterative development  

---

## 👨‍💻 Team Members
- Shashank Raj  
- S. Venkata Sai Kumar Raju  
- Alluri Pavani  
- Bitra Praveeth Sai  
- Haaswith Sai  
- Gaurav Chhajer  
- Swedha  
- Abichellam  
- Vattikutti Ajay  
- S. Mushfira Mehek  

---

## 🚀 How to Run the Code

### 🔑 Prerequisites
- Python **3.8+** installed and on PATH  
- Git installed  
- Visual Studio Code (VS Code)  
- VS Code Extensions: Python, Pylance, Jupyter (install from Extensions view)  
- Azure Speech resource and key (Speech-to-Text): you will need the key and region  

---

### 📂 Step-by-Step Setup

1. **Clone the Repository**
   ```bash
   git clone <repo_link>
   ```

2. **Upgrade pip and Install Dependencies**
   ```bash
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```

3. **Configure Azure Credentials**
   ```bash
   AZURE_SPEECH_KEY=your_azure_speech_key
   AZURE_REGION=your_azure_region
   ```

4. **Secure Credentials**
   - Add `.env` to `.gitignore`  

5. **Run Python Scripts**
   ```bash
   python src/recognize_once.py
   python src/continuous_recognition.py
   ```

---

## 📄 Documentation
- **Milestone Report**: (Docs/milestone1_report.md)
- **Setup_INSTRUCTIONS**: (Docs/Setup_INSTRUCTIONS.md)
