# Smart India Hackathon Workshop
# Date:12-03-25
## Register Number:24900264
## Name:AKASH P
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization

The problem creator's organization is the Ministry of Defence. Specifically, it is related to the Defence Research and Development Organisation (DRDO), which operates under the Ministry of Defence.




## Idea
### Idea for the **Web-Based Selector-Applicant Simulation Software**:

The idea is to create an **intelligent, automated interview system** that simulates a real-life interview experience for both the **candidate** and the **interviewer** (expert). This system would ensure a more efficient, unbiased, and objective recruitment process by:

1. **Tailored Question Selection**: Automatically generating interview questions that are relevant to the **candidate's qualifications**, **role being applied for**, and **level of expertise**.
   
2. **Real-Time Scoring and Evaluation**: Using **AI and NLP** to analyze the candidate's responses for both **relevance** and **depth**, providing **instant feedback** and **scores** for each answer.

3. **Expert Involvement**: Allowing interview experts to manually rate questions for **relevance** and **adjust** the interview process as necessary.

4. **Quantifiable Evaluation**: Assigning a final score based on the **quality of responses** and **question relevance**, enabling accurate assessments of the candidate's **technical knowledge** and **fit for the role**.

5. **Customizable Interview Structure**: The system will support different **interview formats** based on job levels (entry-level, mid-level, senior-level) and can include both **technical** and **managerial** questions.

By automating the question selection, response analysis, and evaluation process, this software would not only streamline the recruitment process but also make it **more consistent, fair, and objective**.

## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/b75e863f-96ec-4c81-a90d-11cc08fb90b2)


## Use Cases

1. Candidate Use Cases
Profile Creation & Setup
Question Response
Receiving Interview Feedback

3. Expert (Interviewer) Use Cases
Login & Profile Management
Viewing Candidate Profile & Questions
Evaluating Candidate Responses
Generating Candidate Evaluation Report

5. System (Automated) Use Cases
Question Generation
Response Evaluation
Generating Candidate’s Report
Security and User Authentication

7. Admin Use Cases
Managing Question Bank
Monitoring System Health & Usage




## Technology Stack


Frontend: React/Vue.js, Bootstrap/Tailwind CSS, WebSockets
Backend: Python (Flask/Django), Node.js (Express), RESTful APIs, GraphQL (optional)
AI/NLP: spaCy, BERT, GPT, TensorFlow/PyTorch
Database: PostgreSQL/MySQL, MongoDB (optional), Redis

## Dependencies

React or Vue.js (for UI development)
Bootstrap or Tailwind CSS (for styling)
Flask or Django (Python frameworks) or Express (Node.js framework)
SQLAlchemy (for ORM, if using Flask)
