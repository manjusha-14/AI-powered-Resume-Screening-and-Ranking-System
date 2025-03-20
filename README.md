# AI-powered-Resume-Screening-and-Ranking-System
# AI-powered Resume Screening and Ranking System  

## *Overview*  
The AI-powered Resume Screening and Ranking System automates the resume screening process using *Natural Language Processing (NLP)* and *Machine Learning (ML)* techniques. It extracts key details such as skills, experience, education, and certifications from resumes and matches them with job-specific criteria to rank candidates based on relevance. The system ensures faster, more accurate, and unbiased candidate selection, improving the overall efficiency of the recruitment process.  

---

## *Motivation*  
Recruiters face challenges in handling a large volume of resumes, leading to delays, human bias, and missed opportunities. Manual screening is time-consuming and inconsistent. An AI-powered system can automate this process using NLP and ML, ensuring faster, more accurate, and unbiased candidate selection.  

---

## *Objectives*  
✔ Automate resume screening and ranking.  
✔ Improve accuracy and fairness in candidate selection.  
✔ Reduce recruitment time and operational costs.  
✔ Provide real-time feedback and adaptive learning.  

---

## *Features*  
✅ Extracts text from PDF resumes using PyPDF2  
✅ Uses TfidfVectorizer to convert text into numerical features  
✅ Calculates similarity using cosine_similarity  
✅ Ranks resumes based on similarity to the job description  
✅ User-friendly interface built with Streamlit  

---

## *Technologies Used*  
- Python  
- Streamlit  
- PyPDF2  
- scikit-learn  
- pandas  
- BERT (for semantic understanding)  
- XGBoost and Random Forest (for ranking)  

---

## *Installation*  
### *Clone the repository*  
```bash
git clone https://github.com/your-repo/resume-screening.git
cd resume-screening
