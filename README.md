📖 Ayah Finder – Quranic Topic & Semantic Search

Ayah Finder is an NLP-powered project that enables users to explore the Quran through topic modeling and semantic similarity search on Urdu translations (Tanzil dataset).

⚡ It combines two strategies:

Topic Modeling (BERTopic) → Automatically clusters ayat into themes (e.g., Mercy, Patience, Faith).

Semantic Similarity (Sentence-BERT) → Finds ayat semantically related to user queries.

🚀 Features

📂 Works on Quran Urdu Translation dataset (from Tanzil).

🔍 Search ayat by themes or meaning.

📊 Automatic topic discovery using BERTopic.

💡 Hybrid approach: filter by topic → rank by semantic similarity.

🎛️ Easy-to-use Gradio UI for searching.

🛠️ Tech Stack

Python 3.12+

BERTopic
 – Topic Modeling

SentenceTransformers
 – Semantic Embeddings

HuggingFace Model: paraphrase-multilingual-mpnet-base-v2 (supports Urdu)

Gradio – Interactive Web UI

Pandas, NumPy, Scikit-learn – Data handling


requirements.txt contains 
bertopic
sentence-transformers
scikit-learn
pandas
numpy
gradio

📊 Example

Input:

رحمت پر مبنی


Output (sample):

Surah 2, Ayah 207
And among mankind is he who sells himself seeking Allah's pleasure. And Allah is kind to His servants.

Surah 3, Ayah 170
Rejoicing in what Allah has bestowed upon them of His bounty...

🌙 Future Work

✅ Add Hadith dataset support.

✅ Multi-language translations (English, Arabic, Urdu).

✅ Deploy on HuggingFace Spaces / Streamlit Cloud.

✅ Add Q&A system on top of semantic search.


