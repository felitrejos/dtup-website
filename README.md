# De Todo Un Poco — DTUP Website

De Todo Un Poco is a digital platform for Costa Rican businesses and entrepreneurs. Born from a Facebook community founded in 2017, the website gives local business owners a dedicated space to showcase their products and services, reach new customers, and be part of a trusted network of Costa Rican commerce.

The platform features a searchable business directory organized by categories, business profiles with contact info and social links, event listings and community content, all managed through an integrated CMS.

## Stack

- **Frontend:** Next.js 16, React 19, TailwindCSS, Framer Motion
- **CMS:** Payload CMS 3.80
- **Database:** MongoDB
- **Storage:** AWS S3 / Cloudflare R2
- **Deployment:** Netlify
- **Package Manager:** Bun

## Development

```bash
bun install
bun run dev        # http://localhost:3000
bun run build
bun run start
```

Admin panel: `http://localhost:3000/admin`

## Environment Variables

```
NEXT_PUBLIC_PAYLOAD_URL
PAYLOAD_SECRET
MONGO_URI
S3_*
```
