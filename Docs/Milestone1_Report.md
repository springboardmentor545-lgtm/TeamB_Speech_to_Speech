# 📝 Milestone 1 Report — AI Powered Real-Time Speech Translation for Multilingual Content

## 🎯 Objective
The objective of **Milestone 1** was to lay the foundation for the **real-time speech translation system** by focusing on **speech recognition** and **data collection**.  

This stage was critical because **accurate recognition of speech is the first step before translation can be implemented**.  

Specifically, the goals were to:  
- Set up **Azure Speech-to-Text** for real-time speech recognition.  
- Collect **sample audio data** in English and Hindi, including live commentary and pre-recorded speech.  
- **Preprocess** the collected datasets to improve clarity, reduce noise, and handle challenges like **Hinglish** speech.  
- Validate recognition scripts to ensure that the system can process speech accurately.  

---

## ⚙️ Steps of Project Setup
1. Installed Python and project dependencies using:  
   ```bash
   pip install -r requirements.txt
   ```  
2. Configured **Azure Speech-to-Text API** with authentication keys.  
3. Collected **live commentary audio samples** in English and Hindi.  
4. Preprocessed datasets for **background noise reduction** and proper labeling.  
5. Stored processed files in the `data/` directory under **language-specific folders**.  

---

## 🎧 Dataset Details
The dataset used during **Milestone 1** consisted of **real-time collected audio samples** in English and Hindi, with some optional Hinglish samples.  

- Files stored in **WAV format** under the `data/` directory.  
- Organized into subfolders by language.  
- Dataset was critical for testing recognition accuracy and preparing for model training in future milestones.  

---

## ⚠️ Challenges Faced
- Encountered a **UnicodeEncodeError** when transcribing multilingual speech.  
- This happened because the Windows terminal uses the default **CP1252 encoding**, which cannot represent Hindi or special Unicode characters.  

### ✅ Solution
- Resolved by explicitly reconfiguring Python’s standard output to use **UTF-8 encoding**.  
- By adding the following line, the application was able to handle and display multilingual characters (including Hindi and Hinglish) without errors:  

```python
import sys
sys.stdout.reconfigure(encoding='utf-8')
```

This ensured **smooth execution of the speech recognition pipeline**.  

---

## 📊 Results

| Language | Accuracy (%) |
|----------|--------------|
| English  | ~80% to 90%        |
| Hindi    | ~70% to 80%        |

---

## ✅ Conclusion
Milestone 1 was successfully completed with:  
- Setup of **Azure Speech-to-Text**  
- **Data collection** in English and Hindi  
- Initial validation of recognition accuracy  

The challenges of noise, API integration, and Hinglish handling were effectively addressed. The outputs demonstrated **good results**, providing a solid base for upcoming milestones.  
