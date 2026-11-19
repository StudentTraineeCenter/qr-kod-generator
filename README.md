# QR Code Generator

A web application for generating customizable QR codes. Built with React, TypeScript, Vite, and Tailwind CSS using the Fluent 2 design system.

**Live Demo:** [Try it here](https://qr-kod-generator-stc.simonstohs99.workers.dev)

## Features

- ✅ Generate QR codes from text or URLs
- 🎨 Customizable foreground and background colors with contrast ratio validation (ISO/IEC 18004)
- 📐 Adjustable resolution (128–4096 px)
- 📄 Export to PNG (raster) and SVG (vector)
- 🔧 Selectable error correction levels (L, M, Q, H)
- 🖼️ Optional center logo overlay with automatic size validation

## Tech Stack

- **React 19** + **TypeScript**
- **Vite** (build tool)
- **Tailwind CSS v4** (styling, Fluent 2 design)
- **qrcode** (QR code generation)

## Local Development

```bash
npm install
npm run dev
```

## Docker Deployment

```bash
docker build -t qr-kod-generator .
docker run -p 8080:80 qr-kod-generator
```

The application will be available at `http://localhost:8080`.

## License

MIT
