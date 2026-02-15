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

## API Configuration

### Environment Variables

Create a `.env` file in the project root:

```bash
# Voice/Mic API (optional - for voice recording features)
MIC_API_KEY=your_mic_api_key
MIC_API_URL=https://api.voiceapi.com/v1

# Speech-to-Text
STT_API_KEY=your_stt_api_key
```

### RevenueCat Configuration

1. Create an account at [RevenueCat.com](https://revenuecat.com)
2. Create products in App Store Connect / Google Play Console:
   - Monthly: $1.99/month - `micowins_monthly`
   - Annual: $9.99/year - `micowins_annual`
3. Configure products in RevenueCat dashboard
4. Add your API key to the purchases service
