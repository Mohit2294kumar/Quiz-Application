Quiz Application 
Project Overview:
This is a Next.js-based Quiz Application built with React and Bootstrap. It's a full-stack interactive quiz platform that tests user knowledge with multiple-choice questions and scoring.

Key Features:
1. User Authentication Flow

Users enter their name before starting the quiz
Button remains disabled until a valid name is provided (input validation)
Name is passed to the quiz component for personalization

2. Quiz Logic

Multiple-choice questions stored in a centralized data structure
Real-time answer tracking with visual feedback
Navigation between questions with validation
Scoring system: 5 points per correct answer
Tracks correct/wrong answers separately
3. Results & Scoring

Displays final score and performance breakdown
Shows correct vs. wrong answer counts
Results page with score analysis (ScoreCard component)

Tech Stack:
Frontend: React 19, Next.js 16 (App Router), Bootstrap 5
Styling: Bootstrap + custom CSS modules
State Management: React Hooks (useState)
Code Quality:
Component-based architecture (Quiz, ScoreCard components)
Separation of concerns (data in QuestionSet.js)
ESLint configured for code standards
Client-side rendering with 'use client' directive