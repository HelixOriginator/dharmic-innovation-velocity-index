Dharmic Innovation Velocity Index (DIVI)

Created by Kallol Chakrabarti (also known as Kallol), Independent Researcher

A world-first framework for measuring the ethical momentum of youth-driven social innovation. DIVI blends dharmic principles, decentralized science, and modern analytics to help young innovators build credible, verifiable, and culturally grounded impact records.

Overview

DIVI is an open-source system that tracks how ethically and effectively a social project evolves. It brings together four core components:

Karma Index — measures community benefit, evidence strength, and ethical alignment.

Kallol Wave Framework — a four-stage cycle mapping motivation and progress (Observation → Reflection → Creation → Dissemination).

Helix Originator Process — a novelty-verification pipeline that generates a project-level identifier similar to a DOI.

Temporal Ethics Layer — optional Panchang-based alignment for users who want cultural or dharmic timing guidance.

The aim is to help students, NGOs, educators, and researchers understand the depth, direction, and credibility of their work.

Why DIVI Matters

Young innovators often face challenges such as:

proving authenticity

building research-ready credentials

demonstrating ethical impact instead of activity

showing originality

dealing with misinformation or inflated claims

DIVI addresses these gaps through structured scoring, transparent logic, and records that anyone can verify.

Key Features
Ethical Velocity Dashboard

Live indicators showing:

community impact

stakeholder engagement

ethical momentum

position within the Kallol cycle

Helix Novelty Check

A lightweight analysis pipeline (stubbed in this version) that reviews text, links, or videos and generates a unique project identifier.

Karma Index Calculator

Scores based on:

magnitude of benefit

certainty of evidence

alignment with dharmic principles

optional temporal ethics

Kallol Wave Tracking

Identifies the current phase and suggests what’s needed to move forward.

Exports and Records

Creates a structured project record that can grow over time and be shared or referenced.

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


Backend runs at:

http://localhost:8000

Frontend (React + Vite)
cd frontend
npm install
npm run dev


Frontend runs at:

http://localhost:5173

Usage

Start backend and frontend.

Open the frontend in your browser.

Create a project and add text, links, or videos.

View the Karma Index, Kallol phase, and Helix identifier.

Save or export your project record.

This version includes the core workflow and leaves room for extensions such as real-time analytics, blockchain verification, and advanced novelty scoring.

Roadmap

Full Helix novelty analysis

Expanded ethical velocity metrics

PDF/CSV export

Multi-language interface

Optional blockchain timestamping

Public API for institutions

Community and mentor-matching layer

Attribution

Created by
Kallol Chakrabarti (also known as Kallol)
Independent Researcher
