# AI Interview Mocker Web Application

**AI Interview Mocker** is a full-stack web application that allows users to practice technical and behavioral interviews with AI-generated questions, real-time video/audio recording, and instant feedback. The platform helps users improve their interview skills by providing detailed evaluations and tracking progress over time.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Architecture](#project-architecture)
- [Future Improvements](#future-improvements)

---

## Overview
The AI Interview Mocker Web Application simulates real interviews using **Gemini AI**. Users can record video and audio answers, transcribed in real-time with speech-to-text, and receive instant AI-generated feedback. The project demonstrates **full-stack development**, AI integration, and interactive frontend features with **Next.js** and **React**.

---

## Features
- **AI-Generated Questions**: Gemini AI generates dynamic interview questions based on category or difficulty.
- **Video & Audio Recording**: Real-time recording of answers with live webcam preview.
- **Speech-to-Text**: Converts spoken answers into text for AI evaluation.
- **Instant Feedback**: Scores and detailed suggestions provided by Gemini AI.
- **Progress Tracking**: Users can review past interviews and monitor improvement.
- **User Authentication**: Secure login/signup using Clerk.
- **Responsive UI**: Built with React and Next.js, fully responsive across devices.
- **Database Management**: Interview sessions, answers, and feedback stored using Drizzle ORM.

---

## Tech Stack
- **Frontend**: Next.js, React, HTML, CSS, JavaScript
- **Backend**: Next.js API Routes, Node.js
- **Database**: Drizzle ORM
- **Authentication**: Clerk
- **AI Integration**: Gemini AI
- **Media Handling**: MediaRecorder API (video/audio)

---

## Project Architecture
- **Frontend**: React components and Next.js pages for UI, responsive design, live webcam preview, and speech-to-text integration.
- **Backend**: Next.js API routes handle interview session creation, sending/receiving data, and interacting with Gemini AI.
- **Database**: Drizzle ORM manages user sessions, answers, feedback, and media metadata.
- **AI Integration**: Gemini AI generates questions and evaluates answers dynamically.
- **Authentication**: Clerk manages secure user signup and login.

---

## Future Improvements
- Move video/audio storage to **cloud storage** (AWS S3, Cloudinary) for scalability.  
- Add multi-language support for AI-generated questions and speech-to-text.  
- Implement real-time scoring and analytics dashboards for deeper insights.  
- Integrate notifications and reminders for scheduled mock interviews.  
- Add advanced NLP evaluation for more detailed AI feedback.
