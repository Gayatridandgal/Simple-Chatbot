# Simple Chatbot

A powerful AI chatbot built using **Gradio** and **Google Generative AI** (Gemini API). This chatbot supports text and speech input, saves conversations, and allows exporting chats in Markdown format.

## Features
- **Supports multiple AI models**: Gemini 1.5 Flash, Gemini 1.5 Pro, Gemini 2.0 Flash Thinking
- **User-friendly interface** with a dark theme
- **Speech-to-text functionality** for voice input
- **Chat history management** (save, load, and export conversations)
- **Customizable creativity (temperature control)**

---
![Screenshot 2025-03-02 140316](https://github.com/user-attachments/assets/654fd48c-0392-4405-8288-59fab899cd2d)


![Screenshot 2025-03-02 141729](https://github.com/user-attachments/assets/dcbec0ef-bd89-43b5-a505-cf2fb7865740)



## Installation & Setup

### **1. Clone the Repository**
```bash
git clone https://github.com/Gayatridandgal/Simple-Chatbot.git
cd Simple-Chatbot
```

### **2. Set Up a Virtual Environment (Optional but Recommended)**
```bash
python -m venv chatbot_env
source chatbot_env/bin/activate  # On Mac/Linux
chatbot_env\Scripts\activate    # On Windows
```

### **3. Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4. Add Your Google Gemini API Key**
Create a `.env` file in the project root and add:
```plaintext
GEMINI_API_KEY=your_api_key_here
```

### **5. Run the Chatbot**
```bash
python app.py
```

---

## Usage
- **Text Input**: Type messages in the text box.
- **Speech Input**: Click the 🎤 button to use voice input.
- **Save Chat**: Click `💾 Save Conversation`.
- **Load Chat**: Select a conversation from the dropdown and click `📂 Load`.
- **Export Chat**: Click `📤 Export as Markdown` to save the chat.
- **Clear Chat**: Click `🗑️ Clear Chat`.

---

## Deployment

To share the chatbot publicly, run:
```bash
python app.py --share
```
Gradio will generate a shareable public link.

---


## Requirements
Ensure you have the following installed:
- **Python 3.x**
- **Pip**
- **Google Generative AI API key**

To install missing dependencies manually:
```bash
pip install gradio google-generativeai python-dotenv speechrecognition pyaudio
```

---

## Troubleshooting
### **PyAudio Installation Issues (Windows)**
If `pip install pyaudio` fails, try:
```bash
pip install pipwin
pipwin install pyaudio
```

### **API Errors**
Ensure your API key is valid and has access to the selected Gemini model.

---

## Author
**Gayatri Dandgal**

---

## License
This project is open-source under the MIT License.

