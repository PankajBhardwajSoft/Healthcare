# Practo Support Agent (CrewAI capstone)

**Track: Practo (Healthcare).**

A domain support agent that answers clinic-policy questions from a written knowledge base and checks appointment status from a seeded dataset. It is built with CrewAI, reviewed by an Autogen team, and served with FastAPI. The full brief is in [CLAUDE.md](CLAUDE.md).

Everything runs under `MOCK_LLM=true` with zero API keys. `CREWAI_DISABLE_TELEMETRY=true` and `OTEL_SDK_DISABLED=true` are set before any crew runs (see `.env.example`).

## Setup

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
```

## Status

Sections for each part are added as the parts are built.
