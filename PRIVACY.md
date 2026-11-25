# Vela privacy policy

Last updated: November 25, 2026

Vela is a Mac app. Most of what it keeps never leaves your Mac. This page says what does, where it goes, and how to remove it.

## On your Mac

- Notes, recordings, transcripts, summaries, chats, projects, the Shelf and settings stay on your Mac, in `~/Library/Application Support/Vela` and `~/Documents/Vela`.
- Your AI keys (Gemini, Claude, ChatGPT) are kept in the Mac's Keychain.
- Speech is recognized on your Mac, unless you choose an AI provider for it in Settings; then the audio goes to that provider.

## AI providers

When you use an AI feature, Vela sends what that request needs (your question, the selected text, a recording's transcript) straight to the AI you chose, with your own key: Google Gemini, Anthropic Claude or OpenAI ChatGPT. Their own privacy policies apply to those requests. Vela doesn't send anything to an AI you didn't choose.

## License key

To activate Vela you enter a license key, which is free. Vela checks the key with its account server and with Creem, the payment service that issues it. If you get the key or donate through Creem, Creem keeps the email and payment details you give it.

## Telegram and WhatsApp

If you connect Vela's bot in Telegram or WhatsApp, the bot runs on Cloudflare and keeps:

- your chat's id or phone number and the name shown in that messenger, your language and time zone;
- notes and reminders you send, until Vela on your Mac picks them up, and reminders until they're sent;
- if you turn the assistant on: your AI key, encrypted; the last 3 days of your conversation with it; and, if you allow it in Vela's settings, a copy of your notes, reminders, tasks and other items, so it can answer about them;
- voice messages are turned into text with Cloudflare Workers AI; the audio isn't kept.

Messages go through Telegram's or Meta's (WhatsApp) servers, under their own privacy policies.

To remove it: send `/disconnect` to the bot, or press Disconnect in Vela → Settings → Messages. Disconnecting Telegram in Vela removes everything the bot keeps for your Mac.

## Usage statistics

Vela sends anonymous usage statistics (which features are used, errors, timings) to improve the app. They never include your texts, notes, names, emails or keys. Turn them off in the intro or in Vela → Settings → About.

## Feedback

When you press **Problem? Share!**, what you write, the files you attach and Vela's recent log go to the developer. Nothing is sent without you pressing Send.

## Children

Vela isn't meant for children under 13.

## Changes and questions

If this policy changes, this page changes with it, with a new date at the top. Questions: press **Problem? Share!** in Vela.
