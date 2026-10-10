# System Design Document Template Builder

Form-driven builder that assembles a complete, well-structured system design document from seven labelled textarea sections and exports it as formatted Markdown.

## Key Features

- Seven standard sections: Context & Motivation, Architecture Overview, Data Model, API Surface, Error Handling, Testing Strategy, Deployment
- Document metadata fields (title, author, version) included in generated output with an auto-generated Table of Contents
- Live character count per section textarea
- localStorage auto-save (debounced 800ms) so content survives page refresh
- Generate Markdown button renders full document preview; Copy to Clipboard sends it to the clipboard
