# MicoWins

A lightweight landing page for MicoWins, focused on promoting micro-wins and daily progress.

## Project Structure

- `web/index.html` — static landing page (HTML/CSS/JS)

## Development Notes

This repository currently does **not** include an Expo or TypeScript project scaffold (`package.json`, `expo`, `tsconfig.json`, or `.ts` sources).

As a result:

- `npx expo install --fix` cannot run successfully without `expo` installed.
- `npx tsc --noEmit` cannot type-check because no TypeScript project/config exists.

## Run Locally

Open the static page directly:

```bash
open web/index.html
```

Or serve with a simple local web server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080/web/
```
