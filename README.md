# PatientTriage.ai

PatientTriage.ai is a safety-first, clinician-supervised emergency-department triage proof of concept built for Accenture Innovation Challenge 2026, Round 2.

## What it demonstrates

- 20 simulated patient records spanning pediatric, adult, geriatric, ambiguous and zero-history scenarios.
- A hybrid, explainable rules engine that produces a 5-level triage recommendation.
- Explicit confidence and uncertainty flags; incomplete or ambiguous presentations are escalated for review rather than silently downgraded.
- A 3x surge simulation and waiting-room reassessment triggers.
- Clinician override capture with mandatory rationale and timestamped audit log.

## Run locally

No package installation is required. Download or clone the repository and open `index.html` in a modern browser.

## Safety and scope

This is an illustrative prototype using synthetic data. It is not a medical device, provides no diagnosis, and must not be used for clinical care. Any production version would require hospital governance, clinical validation, regulatory review, cybersecurity testing and integration with approved EHR systems.

## Assumptions

- India deployment context: DPDP Act 2023 plus applicable clinical/hospital policy.
- 5-level triage scale; final accountability remains with a licensed clinician.
- Data minimization, role-based access, encryption, consent/notice and immutable audit logs are required production controls.

## Repository contents

- `index.html` - complete interactive prototype.
- `README.md` - installation, scope and safety notes.
