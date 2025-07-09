# AI Resume Matcher 🔍🧠

An AI-powered job matching platform that uses OpenAI GPT and Pinecone to semantically match resumes to job descriptions with real-time scoring and vector search.

## 🚀 Features

- 🧠 **LLM-Powered Parsing**: Uses OpenAI GPT to extract key requirements from job descriptions.
- 📄 **Semantic Resume Matching**: Embeds resumes and jobs using OpenAI + Pinecone for contextual search.
- 🔎 **Vector Search with Pinecone**: Matches resumes based on similarity, not just keywords.
- 🧰 **Tech Stack**: Next.js (frontend), Python (API), OpenAI API, Pinecone DB, Vercel deployment.
- 🛠 **Use Case**: Recruiters can instantly identify top-fit candidates with AI recommendations.


## 📦 Folder Structure

ai-resume-matcher/
├── frontend/ # Next.js app
├── backend/ # Python APIs using FastAPI or Flask
├── utils/ # Prompt engineering, parsing
├── README.md

## 🧠 How It Works

1. Job JD is parsed using GPT (via API).
2. Candidate resumes are embedded with OpenAI embeddings.
3. Pinecone stores and indexes vectors.
4. Query job vector against resume vectors.
5. Return top matches with similarity score.

## 🌐 Live Demo

Coming soon... [AI Resume Maker](https://main--ai-resume-builder-07.netlify.app/)

## 👩‍💻 Author

**Reethika Selvam** – [GitHub](https://github.com/Reethikaa05)
