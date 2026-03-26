# Civic issue reporting

*Automatically synced with your [v0.app](https://v0.app) deployments*

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/shubhamj20052005-8892s-projects/v0-civic-issue-reporting)
[![Built with v0](https://img.shields.io/badge/Built%20with-v0.app-black?style=for-the-badge)](https://v0.app/chat/projects/wjoryaGAWUj)

## Overview

This repository will stay in sync with your deployed chats on [v0.app](https://v0.app).
Any changes you make to your deployed app will be automatically pushed to this repository from [v0.app](https://v0.app).

## Deployment

Your project is live at:

**[https://vercel.com/shubhamj20052005-8892s-projects/v0-civic-issue-reporting](https://vercel.com/shubhamj20052005-8892s-projects/v0-civic-issue-reporting)**

## Build your app

Continue building your app on:

**[https://v0.app/chat/projects/wjoryaGAWUj](https://v0.app/chat/projects/wjoryaGAWUj)**

## How It Works

1. Create and modify your project using [v0.app](https://v0.app)
2. Deploy your chats from the v0 interface
3. Changes are automatically pushed to this repository
4. Vercel deploys the latest version from this repository

---

## Chatbot

A floating site-wide chatbot is included.

- UI: `components/chatbot/chat-widget.tsx`
- API: `app/api/chat/route.ts`
- Injection: `app/layout.tsx`

By default, responses are mocked locally. To enable live responses via OpenAI:

1. Set an environment variable `OPENAI_API_KEY`.
2. Restart the dev server.

No configuration is required to use the mocked replies.