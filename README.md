# AI-Resume-Analyzer
AI Resume Analyzer – Resume-to-Job Match (Python, Jina AI & DeepSearch)

This project is a desktop-based GUI application built using Python’s tkinter library. The application ranks candidate resumes against a job posting using both local scoring and AI-powered embeddings with Jina AI and DeepSearch. Users can view the ranked results, candidate details, and AI-generated assessments through an interactive interface.

Overview:
The application demonstrates how to integrate AI APIs, machine learning concepts, and graphical elements into a Python GUI. When launched, the interface displays a title, instructions, a button to analyze resumes, and a scrollable output area where rankings and AI assessments are displayed.

Features:

Graphical interface built with tkinter

Local scoring based on years of experience and education

AI scoring using embeddings and cosine similarity via Jina AI

AI-generated candidate assessments using DeepSearch

Interactive scrollable output displaying detailed resume analysis

How the Program Works:

Local Scoring:

Each candidate is scored based on years of experience and education level

Education is ranked numerically from High School to Master’s Degree

Candidates are sorted in descending order based on their computed score

AI Embeddings Ranking:

Resumes and the job description are converted into embeddings using Jina AI

Cosine similarity between job and resume embeddings determines the AI score

If the API is unavailable, the program defaults to local scoring

DeepSearch Chat Assessment:

For each candidate, a brief AI-generated assessment is provided using DeepSearch

Responses include evaluation of experience, skills, and fit for the job

GUI Interaction:

Users click the “Analyze Resumes” button to perform ranking and analysis

The output box displays the job posting, ranked candidates, scores, and AI comments

A “Close” button allows the user to exit the application

Requirements:

Python 3.x

Packages: numpy, scikit-learn, tkinter, requests

Active Jina AI API key

How to Run:
Run the program from a terminal or command prompt using:
python ai_resume_analyzer.py
