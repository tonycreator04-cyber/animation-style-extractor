# Animation Style Extractor

Portable reconstruction of the Animation Style Extractor product architecture.

Core principle: **analyze HOW an image looks, not WHAT is in it.**

Includes:
- Style Extractor
- Style DNA
- reusable style prompt
- upload workflow
- extraction intensity
- saved styles
- Google-only onboarding flow
- Prompt Studio
- analytics shell
- export/integration shell
- mobile-first dark creative-AI UI

Run:

```bash
npm install
npm run dev
```

The portable analyzer is deterministic and local. The production Floot version can replace it with the existing server-side multimodal AI endpoint without exposing API credentials in the browser.

This package is intended as a portable base for GitHub, Vercel, Replit, or another coding environment.
