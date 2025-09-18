# ⚙️ Setup Instructions — AI Powered Real-Time Speech Translation for Multilingual Content

## 🛠️ Setup Instructions (Weeks 1–2)
This section provides setup instructions for **Weeks 1–2**, covering the process of creating an **Azure Speech resource**, installing the required **SDK**, and setting up the **development environment in Visual Studio Code**.

### 1. Create Azure Speech Resource
1. Log in to the [Azure Portal](https://portal.azure.com/).  
2. Search for **“Speech”** and click **Create Speech Service**.  
3. Select your **subscription**, **resource group**, and **region**.  
4. Choose a **resource name** and **pricing tier**.  
5. Once created, go to the resource and copy the **Key** and **Endpoint URL**.  

### 2. Install Azure Speech SDK
Open **VS Code** and install the Azure Speech SDK using the command:
```bash
pip install azure-cognitiveservices-speech
```

### 3. Configure the Environment
Add your **Azure Speech Key** and **Endpoint** as environment variables or inside a `.env` file for secure usage.

---

## 📄 Final Report

### Week 1
- Created an **Azure Speech resource** on the Azure portal.  
- Configured the resource by obtaining the **API key** and **endpoint URL** required for authentication.  
- Set up the **project environment** by ensuring dependencies and prerequisites were installed.  
- Installed **Visual Studio Code (VS Code)** as the primary development IDE.  

### Week 2
- Installed the **Azure Speech SDK** into the development environment.  
- Connected the SDK with the Azure Speech resource using the **key and endpoint**.  
- Verified installation by running basic **speech-to-text** and **text-to-speech** samples.  
- Began **integration of speech recognition features** into the project pipeline.  
- Observed initial testing results, achieving around **80% accuracy** in recognition tasks.  

---

✨ These steps complete the setup required for beginning the **real-time multilingual speech translation project**.
