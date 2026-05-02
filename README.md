# 🌟 RefineAI: Automated Prompt Enhancement System

An AI-powered system that evaluates user prompts, identifies vague or incomplete inputs, and automatically refines them to generate clear, structured, and high-quality responses using advanced generative AI models.

## 📌 Overview

Many users struggle to get good results from AI because of poorly written prompts. This project demonstrates how **prompt engineering** improves AI output quality.

The system:

* Detects weak or vague prompts
* Provides feedback and suggestions
* Automatically refines the prompt
* Generates improved responses using AI

## 🚀 Features

✔ Prompt quality analysis (GOOD / BAD classification)
✔ Automatic prompt refinement using AI
✔ Warning system for vague prompts
✔ Improved response generation
✔ Retry mechanism for API rate limits
✔ Clean and formatted output display

## 🧠 How It Works

```
User Prompt
     ↓
Prompt Analysis (AI-based)
     ↓
BAD? → Yes → Warning + Suggestion → Refine Prompt
     ↓
Send Refined Prompt to AI Model
     ↓
Generate Final Output
```

## 🛠️ Tech Stack

* **Language:** Python
* **AI Model:** Gemini (via Google AI Studio)
* **Platform:** Google Colab / Local Python
* **Libraries:**

  * `google-generativeai`
  * `textwrap`
  * `time`
  * `sys`

## 📂 Project Structure

```
prompt-refinement-system/
│── main.py
│── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/prompt-refinement-system.git
cd prompt-refinement-system
```

### 2. Install Dependencies

```bash
pip install google-generativeai
```

### 3. Add API Key

Replace this line in the code:

```python
API_KEY = "YOUR_API_KEY"
```

You can get your API key from:
👉 Google AI Studio

## ▶️ Usage

Run the program:

```bash
python main.py
```

### Example Input:

```
write about dogs, state about machine learning etc.
```

### Output:

* ⚠️ Warning for poor prompt
* ❌ Reason for issue
* ✅ Refined prompt
* 🤖 High-quality AI response

## 📸 Sample Output

```
⚠️ WARNING: POOR PROMPT DETECTED
❌ Issue: Too vague and lacks context
✅ Auto-Updating Prompt to: Write an informative article...

FINAL OUTPUT:
[Detailed AI-generated response]
```

## 🎯 Use Cases

* Learning prompt engineering
* AI-based content generation
* Educational demonstrations
* Improving productivity with AI tools

## 📊 Key Concepts Demonstrated

* Prompt Engineering
* Human-AI Interaction
* AI Response Optimization
* NLP-based Systems

## 🔥 Future Improvements

* Add GUI using Streamlit / Gradio
* Add prompt scoring system
* Support multiple AI models
* Save prompt history

## 📚 Learning Outcomes

* Built a real-world AI application
* Understood prompt refinement techniques
* Integrated APIs in Python
* Improved system design skills

## 👨‍💻 Author

**Arpa Kundu**

## ⭐ If You Like This Project

Give it a ⭐ on GitHub and feel free to fork!
