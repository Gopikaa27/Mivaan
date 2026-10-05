# Aniket Ji Turns 29 — Complete Birthday Website

A warm, friendly, mobile-first birthday quiz and message experience for Aniket.

## Project structure

frontend/
  index.html
  The complete birthday website.

backend/
  Code.gs
  Google Apps Script backend.
  README.md
  Backend deployment instructions.

## Frontend features

- Warm cream / blush / lavender visual theme
- One question per screen
- Tailored Aniket × Gopika questions
- Open-ended and multiple-choice questions
- Funny transition messages
- Emotional final question
- Birthday message reveal
- Retake quiz
- Returning visitors can go directly to the message
- Local attempt storage

## Backend features

- Google Apps Script Web App
- Private Google Sheet destination
- One row per completed quiz attempt
- Unique Attempt ID
- Start and completion timestamps
- All 12 quiz answers
- Final answer
- Shared secret token validation

## Important

The ZIP intentionally does NOT contain:

- Your real Google Sheet ID
- Your deployed Apps Script URL
- Your private submission token

Those must be inserted by you after creating the private Google Sheet and Apps Script deployment.

See:

backend/README.md

for the exact setup.

## Recommended deployment

Frontend:
Deploy the frontend to your preferred static hosting provider.

Backend:
Deploy Code.gs as a Google Apps Script Web App.

Data:
Keep the Google Sheet private to Gopika's Google account.
