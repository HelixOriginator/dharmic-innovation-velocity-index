Dharmic Innovation Velocity Index (DIVI)

Created by Kallol Chakrabarti (also known as Kallol), Independent Researcher

A world-first framework that measures the ethical momentum of youth-driven social innovation. DIVI blends dharmic principles, decentralized science, and modern analytics to help young innovators build credible, verifiable, and culturally grounded impact records.

Overview

DIVI is an open-source system that tracks how ethically and effectively a social project grows over time. It brings together four components:

Karma Index — a structured way to measure community benefit, evidence strength, and ethical alignment.

Kallol Wave Framework — a four-stage cycle that maps motivation and progress (Observation → Reflection → Creation → Dissemination).

Helix Originator Process — a novelty-verification pipeline that generates a project-level identifier similar to a DOI.

Temporal Ethics Layer — optional Panchang-based alignment for users who want cultural or dharmic timing cues.

The goal is simple: help students, NGOs, educators, and researchers understand the depth, direction, and credibility of their work.

Why DIVI Matters

Young innovators often struggle with:

proving the authenticity of their projects

getting research-ready credentials

demonstrating ethical impact, not just activity

showing that what they created is unique

navigating misinformation, inflated claims, or vague impact numbers

DIVI makes these challenges easier by offering real scoring, structured documentation, and transparent processes that anyone can audit.

Key Features
Ethical Velocity Dashboard

Live indicators of:

community impact

stakeholder engagement

ethical momentum

phase progress within the Kallol cycle

Helix Novelty Check

A lightweight pipeline (stubbed in this version) that analyzes text, links, or videos and generates a unique identifier for the project.

Karma Index Calculator

Assigns values for:

magnitude of benefit

certainty of evidence

alignment with dharmic principles

temporal ethics (optional)

Kallol Wave Tracking

Shows which phase a project is in and what is needed to reach the next stage.

Exports and Records

A structured project record that grows over time and can be referenced, shared, or extended.

Project Structure
project-root/
├── backend/
│   ├── main.py              # FastAPI entry point
│   ├── models.py            # Data models
│   ├── helix.py             # Novelty & identifier logic
│   ├── karma.py             # Karma Index scoring
│   └── requirements.txt
└── frontend/
    ├── src/
    │   ├── App.tsx
    │   ├── components/
    │   ├── api/
    │   └── styles/
    ├── package.json
    └── vite.config.ts

Installation
Backend (FastAPI)
cd backend
pip install -r requirements.txt
uvicorn main:app --reload


Backend will run at:

http://localhost:8000

Frontend (React + Vite)
cd frontend
npm install
npm run dev


Frontend will run at:

http://localhost:5173

Usage

Start both servers (backend + frontend).

Open the frontend in your browser.

Create a project and add text, links, or video references.

View the computed Karma Index, Kallol phase, and Helix identifier.

Save or export your project record.

This version includes core functionality with room for expansion into real-time analytics, blockchain verification, and deeper novelty scoring.

Roadmap

Integration of real Helix novelty analysis

Expansion of ethical velocity metrics

PDF and CSV export

Multi-language interface

Optional blockchain timestamping for identifiers

Public API for NGOs and institutions

Mentor-matching and community layer

Attribution

Created by:
Kallol Chakrabarti (also known as Kallol)
Independent Researcher

License

Released under the MIT License.
See the LICENSE file for details.
