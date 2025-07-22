# Learning Path Generator with Model Context Protocol (MCP)

This project is a Streamlit-based web application that generates personalized learning paths using the Model Context Protocol (MCP). It integrates with various services including YouTube, Google Drive, and Notion to create comprehensive learning experiences.

## Features

- 🎯 Generate personalized learning paths based on your goals
- 🎥 Integration with YouTube for video content
- 📁 Google Drive integration for document storage
- 📝 Notion integration for note-taking and organization
- 🚀 Real-time progress tracking
- 🎨 User-friendly Streamlit interface

## Prerequisites

- Python 3.10+
- Google ai Studio API Key
- Pipedream URLs for integrations (YouTube and either Drive or Notion)

## Installation

1. Clone the repository:

2. Create and activate a virtual environment:

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Configuration

Before running the application, you'll need to set up:

1. Google API Key
2. Pipedream URLs for:
   - YouTube (required)
   - Google Drive or Notion (based on your preference)

## Running the Application

To start the application, run:
```bash
streamlit run app.py
```

The application will be available at `http://localhost:8501` by default.

## Usage

1. Enter your Google ai studio API key and Pipedream URLs in the sidebar
2. Select your preferred secondary tool (Drive or Notion)
3. Enter your learning goal (e.g., "I want to learn python basics in 3 days")
4. Click "Generate Learning Path" to create your personalized learning plan

## Project Structure

- `app.py` - Main Streamlit application
- `utils.py` - Utility functions and helper methods
- `prompt.py` - Prompt template
- `requirements.txt` - Project dependencies

---

### 1. **App Did Not Start Properly**
- If you saw a prompt for an email address in the terminal, you need to press Enter (or Ctrl+C to skip) to let Streamlit finish launching.
- If the terminal is still waiting for input, the app won't start until you respond.

**What to do:**  
Go to the terminal where you ran the app and:
- If you see the "Email:" prompt, just press Enter to skip.
- Wait for the message:  
  ```
  You can now view your Streamlit app in your browser.
  Local URL: http://localhost:8501
  ```
- Then try refreshing your browser.

---

### 2. **App Crashed or Exited**
- If there was an error in your code or a missing dependency, the app may have crashed.

**What to do:**  
- Check the terminal for any error messages after the email prompt.
- If you see an error, copy it here and I can help debug.

---

### 3. **Port Already in Use**
- If another app is using port 8501, Streamlit may fail to start.

**What to do:**  
- Try running on a different port:  
  ```
  python -m streamlit run learningpath-main/app.py --server.port 8502
  ```
- Then visit [http://localhost:8502](http://localhost:8502).

---

### 4. **Firewall/Antivirus Blocking**
- Some security software may block local servers.

**What to do:**  
- Temporarily disable firewall/antivirus and try again.
- Or, allow Python/Streamlit through your firewall.

---

### Next Steps

1. **Check your terminal for prompts or errors.**
2. **Press Enter if you see the email prompt.**
3. **If the app still doesn't start, let me know what you see in the terminal after running the command.**

Would you like me to try running the app on a different port for you? Or, can you share any error messages you see in the terminal after the last command?

Great! Here’s what you should do next to get your Streamlit app running:

### 1. **Check the Terminal**
- If you see a prompt asking for your email (from Streamlit), just press **Enter** to skip it.
- Wait for the message:
  ```
  You can now view your Streamlit app in your browser.
  Local URL: http://localhost:8501
  ```
- Once you see this, try opening [http://localhost:8501](http://localhost:8501) in your browser again.

---

### 2. **If It Still Doesn’t Work**
- Let me know what you see in the terminal after pressing Enter.
- If there’s an error message, copy it here so I can help you debug.

---

### 3. **Try a Different Port (if needed)**
If you want, I can run the app on a different port for you. Just let me know!

Would you like to proceed with these steps, or do you want me to try running the app on a different port automatically?
