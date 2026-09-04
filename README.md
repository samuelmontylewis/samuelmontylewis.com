# Samuel Monty Lewis' Blog

This is the personal blog and web application for **Samuel Monty Lewis**. The project was built with the help of AI coding tools, mainly **OpenAI Codex** and **Claude Code**, using some of the most capable models available at the time, including **Claude Opus 4.6** and **GPT-5.5**.

AI was used throughout development to help with writing code, debugging, improving the structure of the application, and implementing features.

The website also uses **Supabase** for authentication, including account confirmation and password reset functionality.

## Live demo

Try it out at:

https://samuelmontylewis.github.io/samuelmontylewis.com/

## Run locally

Step 1: Clone the repository:

```bash
git clone https://github.com/samuelmontylewis/samuelmontylewis.com.git
cd samuelmontylewis.com
```

Step 2: Start a local server:

```bash
python3 -m http.server 8000
```

Step 3: Open the website at:

```text
http://localhost:8000
```

## Supabase authentication

Authentication is handled using **Supabase**.

To configure authentication redirects, open:

`Authentication > URL Configuration`

inside your Supabase dashboard.

### Site URL

```text
https://samuelmontylewis.github.io/samuelmontylewis.com
```

### Redirect URLs

Add the following redirect URLs:

```text
https://samuelmontylewis.github.io/samuelmontylewis.com/email-confirmed/
https://samuelmontylewis.github.io/samuelmontylewis.com/reset-password/

http://localhost:8000/email-confirmed/
http://localhost:8000/reset-password/
```

The `localhost` URLs are used during local development, while the GitHub Pages URLs are used for the deployed website.

## AI-assisted development

This project was created with significant assistance from AI.

The main tools used during development were:

* **OpenAI Codex**
* **Claude Code**
* **Claude Opus 4.6**
* **GPT-5.5**

These tools were used as coding assistants for development, debugging, refactoring, and implementing features.

## Licence

This repository is licensed under the **MIT Licence**.

If you use or redistribute this project, please keep the original copyright and licence notice. Credit is appreciated.
