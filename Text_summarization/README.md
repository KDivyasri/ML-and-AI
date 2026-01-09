**📄 AI Document Summarization App**

This project is an AI-powered document summarization application that allows users to upload documents and generate concise, meaningful summaries using large language models. It is built as an interactive Streamlit app for quick experimentation and real-time results.

⸻

🧠 Project Overview

The AI Document Summarization App enables users to summarize long-form content such as PDFs and text documents. It leverages LangChain and LLMs to chunk, process, and summarize documents efficiently while preserving context.

⸻

📦 Project Features

Upload and summarize PDF and text-based documents
Automatic text extraction and preprocessing
Chunk-based summarization for long documents
LLM-powered summaries with contextual coherence
Interactive Streamlit-based user interface
Local-first execution with simple setup

⸻

🧰 Tech Stack

Language: Python
LLM Framework: LangChain
LLM Provider: OpenAI
Tokenization: tiktoken
Document Parsing: unstructured, pdfminer, PyPDF2, pdf2image
UI Framework: Streamlit

⸻

🚀 Getting Started (Local Setup)
```bash
1. Clone the repository
git clone https://github.com/<your-username>/ML-and-AI.git
cd ML-and-AI/Document_Summarization

2. Create a virtual environment
python3 -m venv venv
source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Set environment variables
export OPENAI_API_KEY="your_openai_api_key"

5. Run the application
streamlit run summarization.ipynb

6. Access the application
http://localhost:8501

```
⸻

📂 Project Structure

Document_Summarization/
│
├── summarization.ipynb   Jupyter notebook containing summarization logic
├── requirements.txt      Python dependencies
├── data/                 Sample documents (optional)
└── README.md             Project documentation

⸻

☁️ Deployment

This project can be deployed using Streamlit Cloud or any VM-based service.
```bash
Steps:
git add .
git commit -m "Initial deployment setup"
git push origin main
```
Configure the OPENAI_API_KEY as an environment variable on the deployment platform.
Launch the application using Streamlit.

⸻

💡 Author

Divyasri Kadambi
Python | GenAI | NLP | Data & Cloud Enthusiast

