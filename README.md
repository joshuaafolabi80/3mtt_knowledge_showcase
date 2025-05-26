# 3MTT Knowledge Showcase

Welcome to the **3MTT Knowledge Showcase** project repository. This project is designed as a comprehensive knowledge platform tailored primarily for Nigerian Primary educational content aligned with the national curriculum. The Secondary school application is in the pipeline.

## Project Overview

The repository contains a quiz application and related resources to support learning and assessment for young students. It includes:

- A frontend built with React for seamless user interaction.
- Backend setup using JSON Server serving quiz data in `db.json`.
- Quiz questions spanning various subjects such as Mathematics, English, Science, and more.
- Curriculum-based structure with terms, classes, subjects, and topics for precise content targeting.
- Support for multiple choice questions, scoring, and explanations.
  
## Features

- Dynamic selection of Class, Term, Subject, and Topic for customized quiz generation.
- User-friendly interface optimized for young learners.
- Scoring system with detailed feedback and performance tracking.
- Secure handling of sensitive environment variables (e.g., API tokens) excluded from the repo.

## Getting Started

### Prerequisites

- Node.js and npm installed on your local machine
- Git installed for version control

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/joshuaafolabi80/3mtt_knowledge_showcase.git
   cd 3mtt_knowledge_showcase
````

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the JSON Server to serve quiz data:

   ```bash
   npx json-server --watch db.json --port 3001
   ```

4. Run the React app:

   ```bash
   npm start
   ```

The application will be available at `http://localhost:3000`.

## Project Structure

* `db.json` — JSON Server database containing quiz questions and related data.
* `backend/` — Contains environment files and backend logic.
* `src/` — React frontend source code.
* `.env` — Environment variables file (not included in repo for security).

## Notes on Security

Sensitive files such as `.env` containing API keys or tokens are excluded from this repository for security reasons. Ensure to create your own `.env` file with necessary environment variables before running the project.

## Contact

For questions, suggestions, or collaboration, reach out via email:

**Joshua Afolabi**
Email: [joshuaafolabi80@gmail.com](mailto:joshuaafolabi80@gmail.com)
