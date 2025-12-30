🤖 AI-Powered Customer Support FAQ Chatbot
📌 Project Overview

This project is an AI-powered Customer Support FAQ Chatbot that answers user queries accurately using a hybrid retrieval approach.
It prioritizes exact question matching and falls back to semantic search using sentence embeddings, ensuring reliable and hallucination-free responses.

The chatbot is built using Natural Language Processing (NLP) and Machine Learning, and includes a simple Gradio web interface along with query logging and analytics.

🎯 Key Features

✅ Exact question matching for maximum accuracy

🔁 Semantic search using sentence embeddings for flexible queries

🧠 Intent classification using zero-shot learning

💬 Interactive chatbot UI with Gradio

📊 Query logging and category-based analytics dashboard

⚠️ No hallucinations (retrieval-based answers only)

🛠️ Tech Stack

Python

Sentence Transformers (all-MiniLM-L6-v2)

Hugging Face Transformers

Zero-Shot Classification (BART)

Gradio

Pandas, NumPy, Matplotlib

Google Colab

🧩 Project Architecture

User enters a question

System checks for exact match in FAQ dataset

If not found, uses semantic similarity (embeddings)

Retrieves the most relevant predefined answer

Logs the query and category

Displays answer via Gradio UI

📂 Dataset

Custom Customer FAQ dataset in CSV format

Columns:

Question

Answer

Category

Categories include:

Account

Billing

Technical

Products/Services

Support/Contact

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-faq-chatbot.git

2️⃣ Open in Google Colab or Jupyter

Open app.ipynb

Upload customer_faq.csv if needed

3️⃣ Install Dependencies
!pip install gradio sentence-transformers transformers torch pandas matplotlib

4️⃣ Run All Cells

Launches a Gradio chatbot interface

Ask questions like:

How do I reset my password?

I forgot my login details

📊 Analytics Dashboard

The system logs every query and visualizes:

Number of questions per category

User interaction trends

This helps simulate real-world customer support analytics.

🧠 Why This Project Matters

Unlike many LLM projects that rely purely on generative models, this chatbot:

Avoids hallucinations

Uses deterministic retrieval

Mimics production-grade FAQ systems used in industry

🔮 Future Improvements

🔹 Add RAG with PDF/Document support

🔹 Deploy on Hugging Face Spaces

🔹 Add similarity confidence thresholds

🔹 Multi-language support

🔹 Chat history & memory

👤 Author

Haroon Bacha
Aspiring Data Scientist | ML & AI Enthusiast

🔗 LinkedIn: ([add your LinkedIn profile link here](https://www.linkedin.com/in/haroon-bacha-571657308/))
🔗 GitHub: ([this repository](https://github.com/HaroonIMS/ai-faq-chatbot/new/main?filename=README.md))
