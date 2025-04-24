# Text-Summarization-app-using-Langchain-and-Streamlit

This is a simple and interactive web application that allows users to summarize large blocks of text using powerful LLMs via Langchain and a user-friendly Streamlit interface.
🚀 Features

    📄 Input any long text and get a concise summary

    🧠 Powered by Langchain and language models

    ⚡ Fast, responsive, and runs locally

    🖥️ Streamlit UI for easy access and interaction

  🛠️ Tech Stack

    Langchain

    Streamlit

    OpenAI / HuggingFace LLMs (depending on your integration)

    Python

   Installation & Setup

    Clone the repository

git clone https://github.com/ParthSirohi/Text-Summarization-app-using-Langchain-and-Streamlit.git
cd Text-Summarization-app-using-Langchain-and-Streamlit

Create a virtual environment (optional but recommended)

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies

pip install -r requirements.txt

Run the app

    streamlit run app.py

⚙️ Configuration

Make sure to add your  GROQ API key to a .env file or configure it in the app.

Example .env:

GROQ_API_KEY=your_key_here

📂 File Structure

├── app.py                  # Main Streamlit app
├── summarizer.py           # Langchain logic
├── requirements.txt        # Dependencies
└── README.md               # Project info

🤝 Contributing

Contributions are welcome! Feel free to open an issue or pull request.
📄 License

This project is licensed under the MIT License.
