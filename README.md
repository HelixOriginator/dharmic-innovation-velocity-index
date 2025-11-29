# DIVI

A modular research project generator that helps users create structured summaries, visualizations, citations, and shareable research outputs.

## Overview

DIVI allows users to assemble research projects from text, videos, or external links. It analyzes content, extracts insights, and produces a clean project record that can be extended with citations, visual elements, and export options.

## Features

* Create and manage research projects
* Analyze text, YouTube links, and documents (stubbed for now)
* Auto-generate citations and references
* Basic DOI-style identifier generation
* Frontend preview of project data
* API endpoints for processing and saving projects

## Project Structure

```
project-root/
├── backend/
│   ├── main.py
│   ├── models.py
│   ├── helix.py
│   ├── karma.py
│   └── requirements.txt
└── frontend/
    ├── src/
    │   ├── App.tsx
    │   ├── components/
    │   ├── api/
    │   └── styles/
    ├── package.json
    └── vite.config.ts
```

## Installation

### Backend (FastAPI)

1. Navigate to the backend folder:

   ```bash
   cd backend
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the server:

   ```bash
   uvicorn main:app --reload
   ```
4. The API will be available at:

   ```
   http://localhost:8000
   ```

### Frontend (React + Vite)

1. Navigate to the frontend folder:

   ```bash
   cd frontend
   ```
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the development server:

   ```bash
   npm run dev
   ```
4. Visit:

   ```
   http://localhost:5173
   ```

## Usage

1. Start both backend and frontend.
2. Open the interface in your browser.
3. Create a research project, add inputs, and view the generated output.

## Attribution

Created by **Kallol Chakrabarti**, also known as **Kallol**, Independent researcher.

## License

This project is released under the MIT License. See the `LICENSE` file for details.
