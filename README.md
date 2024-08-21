# ExtraQ

![AI Quiz Generator](https://github.com/MYoussef885/ExtraQ/blob/main/Screenshot%20(36).png)

## Overview

ExtraQ is a web application designed to assist students by generating quizzes from PDF documents. This tool uses the Gemini Pro API to create quizzes based on the text extracted from user-uploaded PDFs. Users can specify the number of questions and their difficulty level, and also ask specific questions about the generated quiz for additional explanations.

## Features

- **PDF Text Extraction**: Extract text from uploaded PDF files using PyPDF2.
- **Quiz Generation**: Generate quizzes based on extracted text using the Gemini Pro API. Users can control the number of questions and difficulty level.
- **Question and Answer Functionality**: Ask specific questions related to the generated quiz and receive detailed answers.
- **User Interface**: Built with Streamlit for a user-friendly experience.
- **Deployment**: Hosted on Hugging Face Spaces for easy access.

## Technologies

- **Gemini Pro API**: For generating quiz questions based on text.
- **PyPDF2**: For extracting text from PDF files.
- **Streamlit**: For building the frontend interface.
- **Hugging Face Spaces**: For deploying the application.
