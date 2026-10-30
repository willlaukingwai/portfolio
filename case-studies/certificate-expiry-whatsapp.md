## Certificate-Expiry Compliance Platform: Hong Kong engineering firm, 2026

**Problem:** Construction workers in Hong Kong must hold valid certificates. Tracking expiry dates by hand across a large workforce is error-prone and creates compliance risk.

**My role:** I architected and built the platform end-to-end. It was the first application on the firm's WhatsApp workforce-engagement roadmap.

**Scope**
- Reads uploaded certificate cards with multimodal AI, and a person reviews the extracted fields.
- Sends automated WhatsApp reminders at 60, 30 and 7 days before expiry.
- Gives HR an admin console to track and manage certificates.

**Outcome:** ~99% field accuracy at ~70% lower inference cost, which made it possible to move to a smaller model.

**Stack:** Gemini (Vertex AI) · TypeScript, React · WhatsApp Business Platform (Twilio) · Google Cloud · Terraform

_Source code is proprietary; this summarises my role and the outcome._
