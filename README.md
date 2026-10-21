# Bloom

A simple life planner built with Angular. Includes a monthly calendar and agenda, personal events and appointments, study sessions and exams with countdowns, daily tasks, and a dated journal with mood check-ins.

## Develop

Requires Node.js 22.22.3+ or Node.js 24.15+. From this directory:

```sh
npm ci --cache /tmp/npm-cache
npm start
```

The development server binds to `0.0.0.0` on port 4200. Use `npm start -- --port 4201` to choose another port.

```sh
npm run build
```

Production files are generated in `dist/bloom/browser`. Serve that directory with a static web server.

## Your data

Plans, tasks, and journal entries are saved in localStorage on the current browser and origin. Start with an empty calendar and add your own plans. Use **Export my space** for a JSON backup. Keep the same browser and server origin to retain access to your data. Clearing browser storage removes it. This version does not include account sync, external calendar integration, recurring events, or background notifications. Exam countdowns are shown inside the app.

Fonts and decorative illustrations are served locally; the app requires no API keys or external services. The decorative SVG illustrations are original project assets. Fonts are distributed by Fontsource under their included open font licenses.
