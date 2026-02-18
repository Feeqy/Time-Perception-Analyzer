# Time Perception Analyzer

A full-stack behavioral analytics dashboard that analyzes how accurately you estimate task durations.

## Overview

Time Perception Analyzer tracks estimated vs actual task duration and provides:

- Accuracy score
- Overconfidence index
- Daily trend analysis
- Correlation analysis (difficulty, mood, distractions)
- Data-driven recommendations
- Interactive visualizations (Chart.js)
- Fully tested backend with pytest

---

## Tech Stack

### Backend
- FastAPI
- SQLAlchemy (async)
- SQLite
- Pytest

### Frontend
- Vanilla JavaScript
- Chart.js
- Custom CSS (dark theme UI)

---

## Features

- Add task entries
- Real-time summary metrics
- Daily error trend chart
- Scatter plot analysis
- Correlation metrics
- Recommendation engine
- Automated backend tests

---

## Running Locally

### Backend

```bash
cd backend
python -m venv .venv
.\.venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
