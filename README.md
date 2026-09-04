# Samuel Monty Lewis' Blog

Personal blog and web application for **Samuel Monty Lewis**.

This application was developed with the assistance of AI coding tools, primarily **OpenAI Codex** and **Claude Code**. During development, I used some of the most capable models available at the time, including **Claude Opus 4.6** and **GPT-5.5**.

AI was used as a development assistant for tasks such as writing code, debugging, improving architecture, and implementing features.

## Authentication

Authentication is handled using **Supabase**.

### Supabase Redirect Configuration

In the Supabase dashboard, navigate to:

`Authentication > URL Configuration`

Set the following URLs.

### Site URL

```text
https://samuelmontylewis.github.io/samuelmontylewis.com
```

### Redirect URLs

```text
https://samuelmontylewis.github.io/samuelmontylewis.com/email-confirmed/
https://samuelmontylewis.github.io/samuelmontylewis.com/reset-password/

http://localhost:8000/email-confirmed/
http://localhost:8000/reset-password/
```

The localhost URLs are used during local development, while the GitHub Pages URLs are used in production.

## Repository

The source code for the project is available here:

https://github.com/samuelmontylewis/samuelmontylewis.com
