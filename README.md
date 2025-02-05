📚 PDF to Vector Knowledge Base

An AI-powered tool designed to transform PDFs into structured text and vector representations, making them easily interpretable by ChatGPT and custom GPT models. This enables advanced document analysis and optimization, particularly for resume tailoring and company culture insights.

🚀 Purpose

This tool extracts text from PDFs and converts them into:
✅ Readable text for AI interpretation (e.g., ChatGPT, custom GPTs)✅ Vector embeddings for similarity analysis and AI-driven recommendations

🎯 Use Cases

🔹 Resume Optimization – Align resumes closely with job descriptions by leveraging AI analysis.🔹 Company & Culture Insights – Combine with the Multi-Document Sentiment Analyzer to extract sentiment trends from company reviews, internal documents, or leadership statements.🔹 Custom GPT Training – Convert documents into structured knowledge bases for enhanced AI understanding.🔹 Beyond ATS Filtering – Go beyond Applicant Tracking Systems (ATS) by refining job applications based on actual company culture insights.

🔧 Installation

1️⃣ Clone the Repository

git clone https://github.com/UsernameTron/PDF_to_Vector.git
cd PDF_to_Vector

2️⃣ Set Up Virtual Environment (Optional)

python3 -m venv venv  
source venv/bin/activate  # macOS/Linux  
venv\Scripts\activate     # Windows  

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Set Up OpenAI API KeyStore your API key securely in Streamlit Secrets or a .env file:

OPENAI_API_KEY=your-api-key-here

⚠ DO NOT commit your API key to the repository!

5️⃣ Run the App

streamlit run app.py

📂 File Structure

📁 PDF_to_Vector/
 ├── 📄 app.py               # Main Streamlit application
 ├── 📄 requirements.txt     # Dependencies
 ├── 📄 README.md            # Documentation (this file)
 ├── 📁 .streamlit/          # API secrets (not to be committed)
 ├── 📁 models/              # Model files (cached)

🛠 How It Works

1️⃣ Upload a PDF document.2️⃣ Extract structured text for AI processing.3️⃣ Generate vector embeddings for semantic similarity analysis.4️⃣ Optimize insights by combining with the Multi-Document Sentiment Analyzer.5️⃣ Download structured text and vector index for AI-driven decision-making.

📊 Optimized for Job Seekers & Researchers

🔹 Refine resumes to match job descriptions with AI precision.🔹 Analyze company sentiment from public reviews, reports, and statements.🔹 Understand job market trends by leveraging AI-powered document analysis.

💡 Contributing

Want to enhance this tool? Fork the repo and submit a pull request! 🚀

📜 License

MIT License – Free to use and modify.

📩 Contact

For questions or feedback, reach out via GitHub Issues or LinkedIn.

⭐ Support the Project

If you find this useful, give it a ⭐ on GitHub to help others discover it!

