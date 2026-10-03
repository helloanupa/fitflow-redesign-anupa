<<<<<<< HEAD
# FitFlow redesign

Coursework technology-selection and architecture starter for IT3060 Lab Exercise 05.

**Status:** Proposed architecture with starter documentation only. This repository does **not** contain a deployed FitFlow app, trained model, production-grade HIPAA/GDPR implementation or real participant data.

## Lab deliverables
- Platform, backend, database and authentication comparison: `docs/technology-comparison.csv`
- Weighted decision matrix: `docs/weighted-decision-matrix.csv`
- Proposed stack and caveats: `docs/tech-stack-summary.md`
- Architecture image: `docs/architecture.png` (Graphviz source `docs/architecture.dot`)
- Architecture Decision Record: `docs/adr-001.md`
- References: `docs/references.md`

## Planned folders
- `frontend/`: Expo React Native + web
- `backend/`: NestJS core API, scoped WebSocket gateway
- `ai-service/`: Python FastAPI inference

## Validation
Run `python scripts/validate_docs.py` (Python 3, standard library only). GitHub Actions performs the same basic documentation check on pushes/PRs.


Do not upload signed consent forms, raw participant notes, photos, tokens or sensitive health records.
    
=======
# fitflow-redesign-anupa
>>>>>>> 78c5d7fa653666ffabb24e8895d254dd79c937f8
