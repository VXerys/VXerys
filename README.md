![MarioCoder](https://github.com/user-attachments/assets/db1f70a4-c525-4e6f-b55e-ac8fe4e991b8)

## Hi, I'm Sechan

**Full-Stack Mobile Software Engineer and Applied AI Engineer** based in Sukabumi, Indonesia.

I build mobile and web products that real people use: a reading app on Google Play, a clinic system that replaced spreadsheets, and a marketplace that won national startup funding. Most of my work is in Flutter, React Native, Next.js and Supabase, with applied AI on top.

### Now

- **Co-Founder & CTO at [Marketiv](https://marketiv.id)**, a marketplace that connects Indonesian MSMEs with local micro-creators. I lead the Next.js web platform and co-built the Appwrite backend for Midtrans payments, escrow and creator withdrawals. The team was funded by P2MW 2026 and received Juara Harapan 2 at KMI EXPO 2026.
- **Mobile Software Engineer Intern at Mangcoding**, where I'm the main contributor to [BookMate](https://play.google.com/store/apps/details?id=com.mangcoding.bookmate2) on Google Play (286 of 326 commits, Flutter and Supabase).
- **Freelance full-stack developer** for local businesses: a clinic information system, a finance system for a garment manufacturer, and an ERP for a motorcycle gear brand.
- **Studying** Informatics Engineering at Universitas Nusa Putra (expected 2027) and following the Next-Gen AI Engineer path at Asah led by Dicoding.

### Selected work

| Project | What it is | Stack | Links |
|---|---|---|---|
| **BookMate** | Reading-community app on Google Play. I built the reading tracker on an atomic Postgres function so two updates can't reset a book's progress, plus the reflection studio and the badge system. | Flutter, GetX, Supabase | [Google Play](https://play.google.com/store/apps/details?id=com.mangcoding.bookmate2) · [Website](https://bookmate-web.vercel.app) |
| **Marketiv** | Marketplace with pay-per-view campaigns and escrow-backed rate cards. Checkout uses idempotency keys, so a retry on a weak connection can't create a second payment. | Next.js 16, Appwrite, Midtrans, Vertex AI | [marketiv.id](https://marketiv.id) |
| **Cartify** | Voice shopping assistant. Speech recognition runs on the phone and only the transcript goes to the LLM, so it works on weak in-store signal. Basis of my SENTIMETER 2026 paper. | React Native, Expo, Groq, Gemini, SQLite | [Repo](https://github.com/VXerys/cartify-app) · [Paper](https://prosiding.sentimeter.nusaputra.ac.id/index.php/prosiding/article/view/104) |
| **Clinic Information System** | Replaced Klinik Cikidang Medika's spreadsheets for registration, queue, records, billing and reports. Sole developer. Migrated 7,493 legacy rows into Postgres behind row-level security. | Next.js 16, Supabase, Vitest | Client work, private |
| **Fluxa** | Offline-first finance app that logs transactions by voice or receipt scan. The LLM fallback only cleans up low-confidence transcripts and is never allowed to change the amount. | Flutter, FastAPI, faster-whisper, Groq | [App](https://github.com/VXerys/fluxa_app) · [Model API](https://github.com/VXerys/fluxa-model) |
| **ArtConnect** | CRM for visual artists with a drag-and-drop sales pipeline that rolls back if the write fails. I led the full-stack work in a team of five. | React, TypeScript, Supabase, Express, Prisma | [Demo](https://artconnect-crm.netlify.app) · [Repo](https://github.com/VXerys/artconnect-crm) |
| **Gunung Puyuh WebGIS** | Map of the neighbourhoods in Gunung Puyuh, Sukabumi, that sit too far from schools and clinics, with 5, 10 and 15 minute service areas. | Leaflet, JavaScript, GeoJSON | [Repo](https://github.com/VXerys/accessibility-gap-analysis-webgis) |

Full case studies are on [sechanalfarisi.dev](https://www.sechanalfarisi.dev).

### Recognition

- Juara Harapan 2, KMI EXPO 2026, Digital Business (Early Stage), with Marketiv
- P2MW 2026 funding recipient (Kemendikbudristek RI), for Marketiv
- First author and presenter, SENTIMETER 2026, Proceedings Vol 5, pp. 62-75
- MTCNA (MikroTik Certified Network Associate), 2026

### Stack

<p>
  <img src="https://skillicons.dev/icons?i=flutter,dart,react,nextjs,ts,tailwind,supabase,postgres,appwrite,firebase,sqlite,py,fastapi,vercel,git&perline=15" alt="Flutter, Dart, React, Next.js, TypeScript, Tailwind CSS, Supabase, PostgreSQL, Appwrite, Firebase, SQLite, Python, FastAPI, Vercel, Git" />
</p>

- **Mobile:** Flutter, Dart, React Native, Expo, GetX, BLoC, offline-first with SQLite and drift
- **Web:** Next.js, React, TypeScript, Tailwind CSS
- **Backend and data:** Supabase, PostgreSQL with row-level security, Appwrite Cloud Functions, Firebase, Midtrans
- **Applied AI:** LLM integration with Groq, Gemini and Vertex AI, on-device speech recognition, FastAPI
- **Quality:** Vitest, Playwright, flutter_test, Sentry, spec-driven development

### How I work

I plan before I build, test every rule that touches money or patient data, and enforce access in the database, so a broken screen can't get around it.

### Work with me

I take freelance mobile and web projects, from first spec to launch. I'm also open to full-time roles and 3 to 6 month internships, remote or hybrid. Email me at **sehanalfarisi9@gmail.com**.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VXerys/VXerys/output/snake-dark.svg" />
  <img alt="Contribution graph eaten by a snake" src="https://raw.githubusercontent.com/VXerys/VXerys/output/snake.svg" />
</picture>
