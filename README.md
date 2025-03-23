# AI-powered-Resume-Screening-and-Ranking-System-P1

1.INTRODUCTION

The AI-powered Resume Screening and Ranking System is designed to assist recruiters in efficiently identifying the most suitable candidates for a given job role. By leveraging Natural Language Processing (NLP) and Machine Learning (ML) techniques, this system automates resume screening, saving time and improving hiring accuracy.

2.PROBLEM STATEMENT

In modern recruitment, organizations receive a vast number of resumes for each job opening. Manually reviewing these resumes is time-consuming, prone to errors, and inefficient. This project aims to automate the resume screening process by utilizing NLP techniques to rank resumes based on their relevance to the provided job description.

3.PROPESED SOLOUTION

The proposed solution utilizes a combination of TF-IDF Vectorization and Cosine Similarity to rank resumes based on relevance. A web application built using Streamlit provides a user-friendly interface for job description input, resume uploads, and ranked result display.

4.SYSTEM DESIGN

The system architecture is composed of five key components:

4.1 ARCHITECTURE DESIGN

![ARCHITETURE](https://github.com/user-attachments/assets/2113991f-b69f-468b-994f-413c78e54317)

4.2 DETAILED EXPLANATION

User Input and Frontend:
Users can enter the job description and upload multiple resumes in PDF format.

Backend Processing:
Resumes undergo parsing and text extraction to prepare data for analysis.

Feature Engineering:
Extracted text is converted into numerical vectors using TF-IDF Vectorization.

Similarity Computation:
The system calculates the similarity score using Cosine Similarity to assess how well each resume matches the job description.

Ranking and Output Display:
Results are stored, sorted, and displayed in ranked order.

4.3 REQUIREMENT SPECIFICATION

  Hardware Requirements
    Processor: Intel i3 or higher
    RAM: 4GB or more
    Storage: Minimum 1GB free space
  Software Requirements
    Python 3.11 or later
    VS Code or any preferred IDE
    Streamlit for frontend development
    scikit-learn, pandas, and NLTK for ML and NLP tasks
    PyPDF2 or pdfplumber for PDF text extraction
    
5.USAGE

1.Enter the Job Description in the text area.
2.Upload multiple PDF resumes using the file uploader.
3.Click on the "Rank Resumes" button to display the top-ranked resumes.

6.FUTURE SCOPE

Integrate advanced NLP models like BERT or GPT for improved contextual understanding.

Implement a deep learning model for enhanced ranking accuracy.

Add multi-language support to cater to global audiences.

Develop interactive data visualization dashboards for insights into candidate skills and experience.

7.CONCLUSION

This AI-powered Resume Screening & Ranking System addresses the challenge of manual resume screening, which is time-consuming and inefficient. By leveraging TF-IDF and Cosine Similarity, the system automates resume ranking, ensuring fast, objective, and accurate candidate shortlisting. With PDF text extraction, real-time ranking, and easy deployment via Streamlit, this project provides an efficient, scalable, and user-friendly solution for recruiters, hiring managers, and job portals. 🚀

💡 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

