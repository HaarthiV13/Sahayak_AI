# Sahayak_AI

[Live Demo](https://sahayak-ai-flax.vercel.app/)

## Overview

**Sahayak_AI** is an AI-powered assistant platform designed to provide intelligent support and automation features. The repository contains both frontend and backend components, built primarily with Python and TypeScript. The project aims to deliver a seamless user experience leveraging modern frameworks and cloud hosting.

## Features

- AI-powered assistance and automation
- Modular architecture for scalable development
- Frontend built with Next.js and Tailwind CSS
- Backend services and Python integrations
- Cloud deployment configuration (Vercel, YAML, etc.)
- Easy customization via JSON and config files

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

### Deployment

- Configuration for cloud deployment is provided in `apphosting.yaml`.
- The application can be hosted on [Vercel](https://sahayak-ai-flax.vercel.app).

## Contributing

Contributions, feedback, and suggestions are welcome! Please submit issues and pull requests via GitHub.

## License

*No license specified yet.*

## Author

Created by [HaarthiV13](https://github.com/HaarthiV13).
