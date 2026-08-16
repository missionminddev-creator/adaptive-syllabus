# adaptive Syllabus

A concept-level adaptive learning platform that transforms a structured syllabus into personalized learning paths.

## Core Idea

The system organizes learning content as:

Syllabus → Topics → Subtopics → Concepts → Questions

Student performance is recorded at the question level and then backtracked through the hierarchy to identify strengths, weaknesses, coverage, and learning progress.

## MVP

The first version will focus on:

- Structured syllabus management
- Topic and subtopic organization
- Concept-level question tagging
- Student question attempts
- Concept-wise performance tracking
- Weakness identification
- Personalized practice recommendations
- Student performance dashboard
- Teacher/admin question-bank management

## Planned Architecture

- **Frontend:** Next.js
- **Backend & Database:** Supabase / PostgreSQL
- **Hosting:** Vercel
- **Authentication:** Supabase Auth
- **AI:** Optional future layer for automatic question tagging

## Adaptive Learning Model

The initial system will use rule-based analytics rather than AI.

Question performance → Concept mastery → Subtopic performance → Topic performance → Syllabus overview

AI may later be introduced primarily for question-bank classification and tagging.

## Project Status

🚧 MVP development

## Vision

Build a scalable learning system where students do not simply track how much of a syllabus they have completed, but understand **what they actually know, what they are weak in, and what they should practice next.**
