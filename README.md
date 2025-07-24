# Freeway Session Assistant

**Freeway Session Assistant** is a HIPAA-friendly Chrome extension designed to improve psychiatric documentation and reduce clinician burnout. It provides structured SOAP templates, real-time session timers, and EHR-ready export tools to streamline mental health workflows.

## 🧠 Key Features

- 📝 Structured SOAP note templates (Psychiatry, Psychotherapy, TMS)
- ⏱️ Start/stop session timer with live duration tracking
- 📄 Export/copy clinical notes in a single click
- 🤖 Local AI assistant (via Ollama) for:
  - Generating SOAP notes from text
  - Diagnosis suggestions (ICD-10 based)
  - Risk assessments and treatment plans

## 🔗 FHIR Integration

This app integrates with EHR systems using **OAuth 2.0** and **SMART on FHIR** protocols. It supports **read-only access** to:

- Patient demographics
- Diagnoses (Conditions)
- Observations (Vitals, Labs, etc.)

### 🔐 Redirect & Launch URLs

- **OAuth Redirect URL:**  
  [`https://oliastfn.github.io/freeway-practicefusion-app/callback.html`](https://oliastfn.github.io/freeway-practicefusion-app/callback.html)

- **SMART Launch URL:**  
  [`https://oliastfn.github.io/freeway-practicefusion-app/launch.html`](https://oliastfn.github.io/freeway-practicefusion-app/launch.html)

## HIPAA & Privacy Notice

- No real patient data is stored, transmitted, or logged by this extension.
- AI features operate **locally** via Ollama (Mistral or LLaMA).
- Designed for HIPAA-friendly environments.

## 🚀 Use Cases

- Used by providers at Freeway Psychiatry to document psychiatry and TMS sessions
- Scalable integration into any FHIR-compliant EHR system
- Can assist in nationwide expansion of efficient mental health workflows

## 📦 Technologies Used

- JavaScript / HTML / CSS (Chrome Extension)
- FHIR (HL7) + OAuth 2.0
- SMART on FHIR Launch Protocol
- Ollama (local LLM AI engine)
 
All functions are read-only and EHR-safe.

