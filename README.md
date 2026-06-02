# Kira — AI Retail Checkout Persona

Demo: open index.html in Chrome on a tablet. No server needed.

## Requirements
- Chrome/Edge (for camera and Web Audio access)
- HTTPS or localhost (camera requires secure context)
  - Run: npx serve . (then open https://localhost:3000 or use ngrok)
- Cartesia API key (already embedded for demo)

## Barcode testing
Use your phone to display barcodes from: barcodesinc.com/generator
Or scan real products.

## Next steps
- Wire Stripe Terminal M2 (£49) for real payments
- Host on Cloudflare Pages for HTTPS (free)
- Add AgentPay transaction logging
