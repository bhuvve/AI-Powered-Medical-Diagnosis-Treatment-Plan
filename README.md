```markdown
# AI-Powered Medical Diagnosis & Treatment Plan

## Overview
This is an AI-powered **medical diagnosis and treatment recommendation** tool built using **Streamlit** and **CrewAI**. It allows users to input patient symptoms and medical history, then generates a diagnosis, treatment plan, and recommended medical tests.

The results are displayed in the app and can also be downloaded as a **DOCX file** for reference.

## Features
- **AI-Powered Diagnosis**: Identifies possible medical conditions based on symptoms.
- **Personalized Treatment Plan**: Provides detailed treatment recommendations.
- **Medical Test Suggestions**: Recommends diagnostic tests with justifications.
- **Document Generation**: Allows users to download results in a Word document.

## Tech Stack
- **Python** (Streamlit, CrewAI, OpenAI API)
- **LLM** (GPT-based language model)
- **CrewAI Tools** (SerperDevTool for search, ScrapeWebsiteTool for web scraping)
- **Environment Variables** (Handled using `dotenv`)

## Installation
### Prerequisites
Ensure you have the following installed:
- **Python 3.8+**
- **pip**
- **Streamlit**

### Steps to Set Up
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/medical-diagnosis-ai.git
   cd medical-diagnosis-ai
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables:**
   - Create a `.env` file in the project root and add your API keys:
   ```env
   OPENAI_API_KEY=your_openai_key
   SERPER_API_KEY=your_serper_key
   ```

5. **Run the Streamlit app:**
   ```bash
   streamlit run app.py
   ```

## Usage
1. Open the web interface in your browser.
2. Enter patient symptoms and medical history.
3. Click **"Get Diagnosis and Treatment Plan"**.
4. View AI-generated results and download the **DOCX report**.


```

## API Keys
This app uses **OpenAI API** and **Serper API** for search functionality. Ensure you have valid API keys added to your `.env` file.


---

### Author: [Your Name]
GitHub: [Your GitHub Username](https://github.com/yourusername)
```

