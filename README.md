# Sahayak.AI
[Project idea](https://github.com/HaarthiV13/Sahayak_AI/blob/main/Project_idea.md)

[Live Demo](https://sahayak-ai-flax.vercel.app/)

[Video Demo](https://drive.google.com/file/d/1wu_saMlWdvXc6e-Oju-TayDv3zUvPz5R/view?usp=sharing)

[Documentation](https://github.com/HaarthiV13/Sahayak_AI/blob/main/sahayak_ai_documentation.pdf)
## Overview

**Sahayak_AI** is like a smart helping hand for teachers. Today, teachers spend so much time on paperwork, planning, and prep that they barely get to do what they love, most teaching and connecting with students. Our project solves that. We built an AI-powered “co-teacher” that works alongside them in the classroom. Using just a voice-first web app, Sahayak.AI can instantly create local-language stories with pictures, turn a photo of a textbook page into custom worksheets for different learning levels, and even generate full lesson plans from a short syllabus. It also supports students directly, answering their questions in simple words and offering fun, adaptive learning games. In short, Sahayak.AI gives teachers back their time, so they can focus on what really matters: their students.

## Features
*   *Story Creator*
    *   Instantly generates engaging, age-appropriate stories and examples that are culturally relevant to students, complete with unique AI-generated illustrations to capture their imagination.

*   *Worksheet Generator*
    *   Allows a teacher to simply upload a photo of any textbook page. The AI analyzes the content and automatically produces three distinct worksheets for easy, intermediate, and advanced skill levels, ensuring every student is appropriately challenged.

*   *Knowledge Assistant*
    *   Acts as a real-time conversational AI. It answers complex student questions with simple, easy-to-understand explanations and analogies, and provides text-to-speech audio to aid comprehension.

*   *Visual Aid Generator*
    *   Creates clear, simple, blackboard-friendly diagrams and sketches from text prompts, helping teachers explain abstract concepts visually without needing artistic skill.

*   *Auto Lesson Planner*
    *   Transforms a weekly syllabus or list of topics into a detailed, time-structured lesson plan, complete with learning objectives, classroom activities, and assessment methods.

*   *Learning Games Arcade*
    *   A suite of fun, interactive learning games (including a Math Quiz, Word Scramble, and Memory Match) with adaptive difficulty to make learning engaging and reinforce key concepts.
      
*   *Role-Play Script Creator*
    *   Creates educational role-play scripts, complete with multi-speaker audio, to facilitate interactive classroom activities.
      
*   *Ask Later Asynchronous Queue:*
    *    Enables teachers to capture student questions during class and receive comprehensive, multi-modal answers (text, image, and audio) later.
## Tech stack
*   *Frontend:*
    *   *Next.js & React:* Utilized the App Router for server-rendered pages, ensuring optimal performance and a fast user experience.
    *   *TypeScript:* Ensured type safety and maintainability across the project.
    *   *Tailwind CSS & ShadCN UI:* Created a professional, responsive, and accessible user interface with a modern design system.

*   *Backend & AI Integration:*
    *   *Firebase Genkit:* Orchestrated all backend AI logic. Genkit was used to define complex, multi-step "flows" that chain together calls to various AI models.
    *   *Google AI (Gemini Models):*
        *   *Gemini 1.5 Flash:* For all text generation, summarization, and conversational AI tasks.
        *   *Gemini Pro Vision:* To analyze the content of uploaded textbook images.
        *   *Gemini Image & Audio Models:* For generating visual aids, illustrations for stories, and text-to-speech functionality.

*   *Deployment:*
    *   *Vercel:* The application is hosted on Vercel, which provides a seamless environment for deploying Next.js applications, including serverless functions for the backend logic.
## Repository Structure

```
├── .gitignore
├── .idx/
├── .vscode/
├── Project_idea.md
├── apphosting.yaml
├── components.json
├── next.config.ts
├── package-lock.json
├── package.json
├── postcss.config.mjs
├── src/
├── tailwind.config.ts
├── tsconfig.json
├── venv/
```

- **src/**: Source code for the application.
- **venv/**: Python virtual environment.
- **.vscode/**, **.idx/**: Editor and indexing configs.
- **Project_idea.md**: Project concept and planning notes.
- **components.json**: UI/component definitions.
- **apphosting.yaml**: Cloud deployment configuration.
- **next.config.ts**, **tailwind.config.ts**, **postcss.config.mjs**: Frontend build and styling configs.

## Getting Started

### Prerequisites

- Node.js & npm
- Python (for backend/AI tasks)
- Vercel CLI (optional for deployment)

### Installation

```bash
# Clone the repository
git clone https://github.com/HaarthiV13/Sahayak_AI.git
cd Sahayak_AI

# Install Node.js dependencies
npm install

# Set up Python environment
python3 -m venv venv
source venv/bin/activate
# Install Python dependencies as needed
```

### Running Locally

```bash
# Start frontend (Next.js)
npm run dev

# [Optional] Run backend Python scripts
python src/main.py
```

## Contributing

Contributions, feedback, and suggestions are welcome! Please submit issues and pull requests via GitHub.


## Author

Created by [Sriram Ramanadham](https://github.com/sriram0328)  [Haarthi Vallabhaneni](https://github.com/HaarthiV13)  [Abdul Saleem](https://github.com/ShaikAbdulSaleem).
