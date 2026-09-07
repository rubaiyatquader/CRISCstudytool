# CRISC Study Tool

A browser-based CRISC exam study aid with quick scenario quizzes, weighted practice tests, and weak-area retraining loops inspired by short daily learning apps.

## Single-file deployment

The complete application (HTML, CSS, JavaScript, and question data) lives in
`index.html`. It has no dependencies, build output, external assets, or network
requests. Upload that one file to any static host, including GitHub Pages.

## Source basis

The tool is aligned to the current ISACA CRISC exam content outline and the 2025 job-practice update for exams available from November 3, 2025. Source references checked on August 24, 2026: ISACA CRISC exam content outline and ISACA CRISC job-practice update announcement.

- Domain 1: Governance — 26%
- Domain 2: Risk Assessment — 22%
- Domain 3: Risk Response and Reporting — 32%
- Domain 4: Technology and Security — 20%

Question content is original and scenario-based. It is intended for study support and is not official ISACA exam content.

## Run locally

```bash
npm run dev
```

## Build

```bash
npm run build
```
