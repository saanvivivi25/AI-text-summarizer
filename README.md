AI Text Summarizer System

Overview
AI Text Summarizer System is a Python-based application that uses Google's Gemini API to generate intelligent summaries from user-provided text. The application stores summaries in a SQLite database and allows users to search, view, delete, and export summaries to Word documents.
The project demonstrates the integration of Artificial Intelligence, APIs, databases, file generation, and menu-driven programming in Python.
________________________________________
Features
•	Generate AI-powered summaries using Gemini API
•	Generate key points and action items
•	Store summaries in a SQLite database
•	View all stored summaries
•	Search summaries by ID
•	Delete summaries from the database
•	Export summaries to Word documents (.docx)
•	Automatic timestamp generation for each summary
•	Menu-driven command-line interface
________________________________________

Gemini API Setup
Obtain a Gemini API key from Google AI Studio and replace:
genai.configure(api_key="YOUR_GEMINI_API_KEY")
with your API key.
________________________________________

Menu
===== AI TEXT SUMMARIZER =====
1. Generate Summary
2. View Database
3. Search Summary by ID
4. Export to Word
5. Delete Summary
6. Exit
________________________________________
Example Workflow
User enters article
        ↓
Gemini API generates summary
        ↓
Summary stored in SQLite database
        ↓
User can view/search/delete summaries
        ↓
Export summaries to Word document
________________________________________
Learning Outcomes
This project demonstrates:
•	API integration using Google Gemini
•	Prompt engineering
•	Database creation and management with SQLite
•	SQL operations (CREATE, INSERT, SELECT, DELETE)
•	File generation using python-docx
•	Exception handling
•	Functions and modular programming
•	Menu-driven application development
•	Persistent data storage


