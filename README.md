# QR-Based PDF Catalogue Viewer

A minimal PDF viewer that uses QR codes to navigate to specific pages in the Indonesia Pavilion Catalogue.

## Features

- 📄 Browser's native PDF reader (no custom UI)
- 🔗 QR code-based page navigation
- ⚡ Static hosting on Vercel
- 📱 Mobile-friendly

## How It Works

Generate QR codes with URLs like:
- `https://your-site.vercel.app/?page=1`
- `https://your-site.vercel.app/?page=5`
- `https://your-site.vercel.app/?page=10`

When scanned, the QR code opens the PDF directly to that page.

## Deployment

### Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/mmcoder005/qr-pdf-catalogue)

Or use Vercel CLI:
```bash
npm install -g vercel
vercel
```

## Local Development

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view.

## QR Code Generation

Use any free QR code generator:
- [QR Code Generator](https://www.qr-code-generator.com/)
- [QRCode Monkey](https://www.qrcode-monkey.com/)

## License

MIT
