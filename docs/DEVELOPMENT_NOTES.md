# Development Notes

## Objective

The project is designed to help users verify news claims by comparing the input text with evidence collected from public sources.

## Main Modules

- `src`: React frontend, interface components, and styling.
- `backend/app`: FastAPI routes, schemas, evidence collection, scoring, and verdict logic.
- `backend/data`: Local data used by the backend during analysis.

## Design Approach

- Keep the interface focused on entering a claim, viewing evidence, and understanding the final verdict.
- Show confidence and source references clearly so the result is explainable.
- Keep frontend and backend responsibilities separate for easier testing and maintenance.
