# Ironside Epoxy Website

Premium decorative epoxy flooring website for Ironside Epoxy, serving all of North Carolina.

## Running Locally

To serve the site locally, you'll need [Node.js](https://nodejs.org/) installed.

### 1. Install dependencies

```bash
npm install
```

### 2. Start the local server

```bash
npm start
```

This will start a local HTTP server on **http://localhost:8080** and automatically open it in your default browser.

### Alternative: Quick start without installing dependencies

If you have Node.js installed, you can also run the site directly with:

```bash
npx http-server . -p 8080 -o
```

Or with Python (no install needed):

```bash
# Python 3
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

## Pages

- `index.html` — Home page
- `services.html` — Services
- `our-work.html` — Project gallery
- `what-is-epoxy.html` — What is Epoxy?
- `contact.html` — Contact form
- `careers.html` — Careers

## Deployment

This site is deployed automatically via **GitHub Pages** from the `main` branch at [ironsideepoxy.github.io](https://ironsideepoxy.github.io).
