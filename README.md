# Study Assistant - starter

A starter repository for the CSC10014 Smart Virtual Assistant project.

## Setup

Prerequisites: Python 3.10+, Git.

```bash
git clone git@github.com:<your-username>/lab01-<your-username>.git
cd lab01-<your-username>

# Create the virtual environment
python -m venv .venv

# Activate the environment (Windows)
.venv\Scripts\Activate.ps1

# Install dependencies
pip install -r requirements.txt
pip install -e .    
## Run

python -m assistant "where is the IT helpdesk?"
# Expected output: IT Helpdesk, E.005, Mon-Fri 08:00-17:00

## Test

Bash
pytest -q
# Expected output: 4 passed in 0.01s

## Project structure

src/assistant/: application code (backend)

tests/: automated tests

docs/: brief, blueprint, ADRs, logbook, reports

data/: small, non-sensitive sample data

ui/: user interface

scripts/: helper scripts

## Troubleshooting
PowerShell blocks Activate.ps1: Run Set-ExecutionPolicy -Scope CurrentUser RemoteSigned

"No module named assistant": You forgot pip install -e . or the virtual environment is not active.