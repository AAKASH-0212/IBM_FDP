📚 Smart Study Generator Agent
🚀 AI-Powered Smart Study Assistant using LangFlow, IBM watsonx.ai, IBM Granite Models & Retrieval-Augmented Generation (RAG)
📖 Project Overview

The Smart Study Generator Agent is an intelligent AI-powered learning assistant designed to help students organize and simplify their study materials. Instead of spending hours creating notes, flashcards, and quizzes manually, students can upload their educational documents and instantly receive personalized learning resources.

The system leverages Retrieval-Augmented Generation (RAG) with IBM Granite Foundation Models to understand uploaded documents, retrieve relevant information, and generate accurate, context-aware responses.

Whether you're preparing for exams, revising concepts, or learning a new subject, the Smart Study Generator Agent acts as your personal AI study companion.

🎯 Problem Statement
Problem Statement No. 13 – Smart Study Generator Agent

Modern students often struggle with large volumes of educational content scattered across:

📄 Lecture Notes
📚 Textbooks
📑 Research Papers
🎥 YouTube Tutorials
🌐 Online Learning Resources

Traditional study applications only provide static notes or flashcards and cannot understand the actual learning material uploaded by students.

The Smart Study Generator Agent solves this problem by using Agentic AI and Retrieval-Augmented Generation (RAG) to automatically analyze study materials and generate personalized educational content tailored to each learner.

✨ Key Features
📂 Document Upload

Supports multiple study material formats:

PDF
DOCX
TXT
🤖 AI-Powered Document Understanding

Automatically reads and understands uploaded documents using IBM Granite Foundation Models.

📄 Smart Summary Generation

Generates concise and accurate summaries that highlight the most important concepts.

📝 Revision Notes

Creates easy-to-understand revision notes for quick exam preparation.

🧠 Flashcard Generation

Automatically generates interactive flashcards for effective memory retention.

❓ MCQ & Quiz Generator

Creates multiple-choice questions and practice quizzes based on uploaded content.

📅 Personalized Study Planner

Generates customized daily study schedules based on the uploaded material.

💬 AI Question Answering

Allows students to ask questions directly from their uploaded notes and receive context-aware answers.

🔍 Retrieval-Augmented Generation (RAG)

Retrieves only the most relevant information from uploaded documents before generating responses, ensuring greater accuracy and reduced hallucinations.

🎓 Interactive AI Study Assistant

Provides continuous support throughout the student's learning journey.

🛠️ Technology Stack
Technology	Purpose
LangFlow	Visual AI Workflow Builder
IBM watsonx.ai	AI Foundation Model Platform
IBM Granite Foundation Model	Large Language Model
IBM Granite Embedding Model	Semantic Vector Embeddings
Retrieval-Augmented Generation (RAG)	Context-Aware Retrieval
Chroma Vector Database	Vector Storage & Knowledge Base
Python	Backend Development
LangChain	AI Pipeline Integration
Document Loader	Reads Uploaded Documents
Text Splitter	Splits Documents into Chunks
🏗️ System Architecture
                     Student
                        │
        Upload Study Material / Ask Questions
                        │
                        ▼
                LangFlow Workflow
                        │
                        ▼
                Document Reader
                        │
                        ▼
                  Text Splitter
                        │
                        ▼
          IBM Granite Embedding Model
                        │
                        ▼
             Chroma Vector Database
            (Knowledge Base / RAG)
                        │
         Retrieve Relevant Document Chunks
                        │
                        ▼
                IBM watsonx.ai
         IBM Granite Foundation Model
                        │
                        ▼
          Smart Study Generator Agent
                        │
 ┌──────────┬──────────┬──────────┬──────────┬──────────┐
 │          │          │          │          │
Summary  Notes   Flashcards   MCQs   Study Plan
                        │
                        ▼
                AI Chat Response
🔄 Workflow
Step 1

The student uploads study materials such as lecture notes, PDFs, or textbooks.

↓

Step 2

The Document Loader extracts all textual content.

↓

Step 3

The Text Splitter divides large documents into smaller chunks.

↓

Step 4

IBM Granite Embedding Model converts text chunks into semantic vector embeddings.

↓

Step 5

The embeddings are stored in the Chroma Vector Database.

↓

Step 6

When the student asks a question, the RAG pipeline retrieves the most relevant document chunks.

↓

Step 7

IBM Granite Foundation Model generates an accurate, context-aware response.

↓

Step 8

The Smart Study Generator produces:

Smart Summaries
Revision Notes
Flashcards
MCQs
Personalized Study Plans
AI-powered Answers
🤖 Agentic AI Capabilities

Unlike traditional chatbots, this system functions as an intelligent Agentic AI Assistant.

The AI agent autonomously:

📖 Understands uploaded documents
🔍 Retrieves relevant knowledge using RAG
📝 Generates summaries
📄 Creates revision notes
🧠 Produces flashcards
❓ Generates quizzes
📅 Builds personalized study plans
💬 Answers contextual questions
🎯 Adapts to individual learning requirements

This creates a dynamic and personalized learning experience.

🌟 Project Highlights

✅ Agentic AI-Based Learning Assistant

✅ IBM Granite Foundation Models

✅ Retrieval-Augmented Generation (RAG)

✅ Context-Aware AI Responses

✅ Intelligent Document Understanding

✅ Automated Study Resource Generation

✅ Personalized Learning Experience

✅ Interactive Exam Preparation

✅ Visual AI Workflow using LangFlow

📸 Screenshots
LangFlow Workflow
screenshots/workflow.png
AI Chat Output
screenshots/output.png
⚙️ Installation Guide
Clone the Repository
git clone https://github.com/AAKASH-0212/IBM_FDP.git
Navigate to the Project
cd Smart-Study-Generator-Agent
Install LangFlow
pip install langflow
Launch LangFlow
langflow run
Open in Browser
http://localhost:7860
Configure the Following Credentials
IBM watsonx.ai API Key
IBM Project ID
IBM Endpoint URL
Import the Smart Study Generator Flow

After configuration, import the provided LangFlow workflow to begin using the application.

💬 Example Prompts
Summarize the uploaded lecture notes.
Generate revision notes for this chapter.
Create 20 multiple-choice questions.
Generate flashcards from the uploaded PDF.
Explain Artificial Intelligence in simple language.
Explain Machine Learning with examples.
List the most important exam topics.
Create a 7-day study timetable.
What are the advantages of Artificial Intelligence?
Ask questions only from my uploaded notes.
🚀 Future Enhancements
🎤 Voice-Based AI Assistant
🖼️ OCR Support for Handwritten Notes
🌍 Multi-Language Learning
📊 Student Performance Dashboard
📈 AI-Based Performance Prediction
🧠 Concept Map Generation
📱 Android & iOS Mobile Application
☁️ Cloud Deployment
🔔 Smart Revision Reminders
🎯 Adaptive Learning Recommendations
👨‍💻 Developer
AAKASH KUSHWAHA

Computer Science Assistant Professor | Full Stack Developer | AI & Machine Learning Enthusiast

Passionate about developing AI-powered applications that simplify education, improve productivity, and create intelligent learning experiences using modern technologies such as IBM watsonx.ai, IBM Granite Models, LangFlow, Python, and Retrieval-Augmented Generation (RAG).

🙏 Acknowledgements

Special thanks to:

IBM SkillsBuild
IBM watsonx.ai
IBM Granite Foundation Models
LangFlow Community
Chroma Vector Database
Open Source AI Community
📄 License

This project has been developed for educational, research, and innovation purposes as part of the IBM SkillsBuild University Engagement Program.

⭐ Support the Project

If you found this project helpful, consider giving the repository a ⭐ on GitHub. Your support encourages future development and helps others discover the project.
