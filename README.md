# AI Cold Email Writer

Web form → Gemini writes email → Code node cleans output → Gmail sends it.

## What It Does

- Webhook captures lead data from frontend form
- Gemini generates personalized cold email using structured prompt
- Code node strips filler text and markdown from raw AI output
- Gmail sends clean, professional email automatically

## Tech Stack

- n8n
- Google Gemini
- Code node (JavaScript)
- Gmail (OAuth)
- Webhook



