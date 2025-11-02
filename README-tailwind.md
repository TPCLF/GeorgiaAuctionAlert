# Tailwind build instructions (auctions app)

This project includes a minimal Tailwind setup inside the `auctions` app at `auctions/static_src`.

Quick start:

1. Install npm dependencies

```bash
cd auctions/static_src
npm install
```

2. Build production CSS

```bash
npm run build
```

3. Or run in watch/dev mode (rebuilds CSS on change)

```bash
npm run dev
```

The built CSS will be written to `auctions/static/css/dist/styles.css` which Django will serve in DEBUG mode.
