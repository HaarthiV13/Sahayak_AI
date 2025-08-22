# Sahayak.AI

## Overview

**Sahayak_AI** is like a smart helping hand for teachers. Today, teachers spend so much time on paperwork, planning, and prep that they barely get to do what they love, most teaching and connecting with students. Our project solves that. We built an AI-powered “co-teacher” that works alongside them in the classroom. Using just a voice-first web app, Sahayak.AI can instantly create local-language stories with pictures, turn a photo of a textbook page into custom worksheets for different learning levels, and even generate full lesson plans from a short syllabus. It also supports students directly, answering their questions in simple words and offering fun, adaptive learning games. In short, Sahayak.AI gives teachers back their time, so they can focus on what really matters: their students.

## Features
*   *Hyperlocal Content Creator*
    *   Instantly generates engaging, age-appropriate stories and examples that are culturally relevant to students, complete with unique AI-generated illustrations to capture their imagination.

*   *Differentiated Worksheet Generator*
    *   Allows a teacher to simply upload a photo of any textbook page. The AI analyzes the content and automatically produces three distinct worksheets for easy, intermediate, and advanced skill levels, ensuring every student is appropriately challenged.

*   *Knowledge Assistant*
    *   Acts as a real-time conversational AI. It answers complex student questions with simple, easy-to-understand explanations and analogies, and provides text-to-speech audio to aid comprehension.

*   *Visual Aid Generator*
    *   Creates clear, simple, blackboard-friendly diagrams and sketches from text prompts, helping teachers explain abstract concepts visually without needing artistic skill.

*   *Auto Lesson Planner*
    *   Transforms a weekly syllabus or list of topics into a detailed, time-structured lesson plan, complete with learning objectives, classroom activities, and assessment methods.

*   *Learning Games Arcade*
    *   A suite of fun, interactive learning games (including a Math Quiz, Word Scramble, and Memory Match) with adaptive difficulty to make learning engaging and reinforce key concepts.

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

## License

*No license specified yet.*

## Author

Created by [Sriram Ramanadham](https://github.com/sriram0328)  [Haarthi Vallabhaneni](https://github.com/HaarthiV13)  [Abdul Saleem](https://github.com/ShaikAbdulSaleem).
