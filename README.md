# Thought Chisel

**AppADay — App #067**
Category: AI-Powered (A)
Date: 2026-07-13

A voice-powered Socratic idea refiner. Speak your raw thought aloud, and Claude distills it into one sharp sentence, then asks a pointed follow-up question read aloud via Speech Synthesis. Three rounds of speak-listen-refine chisel your ramble into a razor-sharp concept with key tensions worth exploring.

## How It Works

1. Tap the microphone and talk through whatever you're thinking — ramble freely.
2. Tap again to stop. Claude distills your speech into one clear sentence and generates a follow-up question.
3. The app reads the follow-up question aloud. When it finishes, the mic reactivates automatically.
4. Respond to the question out loud. Three rounds total.
5. On the final round, Claude delivers your fully chiseled idea with key dimensions to explore.

## Technical Details

- **Speech Input:** Web Speech API (`SpeechRecognition` / `webkitSpeechRecognition`) with live transcript preview.
- **Speech Output:** SpeechSynthesis API reads follow-up questions aloud. Voice selection available in settings.
- **AI Model:** Claude Sonnet 4.6 via the Anthropic API. API key stored in localStorage via the settings gear.
- **Browser Support:** Chrome (desktop/Android), Safari (iOS 14.5+). Requires microphone permission.
- **No build step, no dependencies.** Single-file vanilla HTML/CSS/JS.

## Part of AppADay

One complete, functional, mobile-friendly web app shipped every day.

[View all apps →](https://augustineiacopelli.github.io/appaday/)
