# JARVIS — iPhone PWA

A privacy-first, installable voice assistant prototype for iPhone.

## Run
Open `index.html` over HTTPS. On iPhone Safari, tap **Share → Add to Home Screen** after GitHub Pages is enabled.

## Features
- Futuristic dark UI and push-to-talk voice recognition (where supported)
- Basic Hinglish greeting, date and time commands
- Spoken responses via browser speech synthesis
- No API keys, tokens, or cloud AI endpoint in client code
- No always-on microphone, hidden monitoring, or arbitrary app access

## Limitations
Browser speech recognition availability varies on iOS and may use browser/vendor speech services. No full AI model is connected. iOS limits direct control of other apps; approved integrations may use Shortcuts or app-specific APIs.

## Deployment
In GitHub repository **Settings → Pages**, select **Deploy from a branch**, branch **master**, folder **/(root)**. Once deployed, open the HTTPS URL in Safari and use **Add to Home Screen**.

## Security
Never put provider API keys in frontend JavaScript or GitHub Pages. Future AI features should use a separately hosted authenticated backend with rate limits, key management and explicit user confirmations for sensitive actions.
