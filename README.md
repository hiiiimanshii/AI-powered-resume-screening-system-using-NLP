# *AI-Powered Resume Screening System Using NLP*   

### *Overview*  
The *AI-powered Resume Screening System* is an advanced *Natural Language Processing (NLP) based application* designed to automatically analyze and rank resumes based on their relevance to a given job description. This system eliminates manual screening, enhances efficiency, and ensures a fair, data-driven candidate evaluation process.  

### *Key Features*  
✅ *Automated Resume Parsing* – Extracts candidate information such as name, email, and skills using *Named Entity Recognition (NER)*.  
✅ *Text Preprocessing* – Cleans and normalizes resume content by removing stop words, lemmatizing, and handling special characters.  
✅ *Semantic Matching with BERT* – Uses *Sentence-BERT (SBERT)* embeddings to measure the similarity between resumes and job descriptions.  
✅ *Resume Ranking* – Assigns a similarity score to each resume and ranks them based on job fit.  
✅ *Scalability & Automation* – Can process multiple resumes at once and integrate with HR software.  

### *Technology Stack*  
🔹 *Programming Language* – Python  
🔹 *Libraries & Frameworks* – spaCy, pdfplumber, sentence-transformers, scikit-learn, NumPy, Flask (for API deployment)  
🔹 *Machine Learning Techniques* – Named Entity Recognition (NER), TF-IDF, Cosine Similarity, Sentence-BERT  
🔹 *Deployment* – Flask API, Streamlit UI, or Cloud-based services like AWS/GCP  

### *How It Works?*  
1. **Extracts text from resumes (PDF format) using pdfplumber**.  
2. *Cleans and preprocesses text* to remove noise and improve readability.  
3. *Uses NLP models to identify key entities* (Name, Email, Skills, Experience, etc.).  
4. *Compares resume content with the job description* using *BERT embeddings*.  
5. *Computes a similarity score* and ranks candidates based on relevance.  

### *Use Cases*  
✅ *HR & Recruitment Agencies* – Automates resume shortlisting, reducing hiring time.  
✅ *Job Portals* – Integrates into job platforms for personalized job recommendations.  
✅ *Corporate Hiring* – Assists hiring managers in filtering high-quality candidates.  

### *Future Enhancements*  
🚀 *Fine-tuned BERT for better resume parsing*  
🚀 *Support for multiple languages*  
🚀 *Integration with LinkedIn API for live job recommendations*  
🚀 *Building an interactive web app for real-time resume uploads*  

This AI-driven resume screening system transforms recruitment, ensuring *efficient, unbiased, and accurate candidate selection*! 🚀
