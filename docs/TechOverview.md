> 🔒 Authorship + Ownership retained by **EcoNexus Systems OÜ**  
> This repo is a cryptographic proof of architecture and authorship.


OneWorldLingo – Technical Architecture Overview (MVP 1)

Applicant Entity:
OneWorldLingo (under parent: EcoNexus Systems OÜ – Estonian e-Residency, reg. code 17218648)

Business Model:
AI-powered SaaS platform for multilingual transcription and document translation. Optimized for EU regulatory compliance, privacy-first deployment, and modular scalability.

1. Mission Statement:
To deliver rapid, compliant, and user-friendly transcription and translation tools through a scalable, cloud-native SaaS platform—prioritizing privacy, accessibility, and cost-effectiveness for European users and institutions.

2. Current MVP Functionality (Feature Complete):

    Upload .mp3 or .wav → Receive AI-transcribed text via OpenAI Whisper

    Upload .txt → Receive instant DeepL translation (multi-language)

    Supabase-authenticated dashboard with role-based access control

    Feature scaffolding in place for future subscription and billing tiers

    Deployment-ready infrastructure, pending Stripe integration finalization

3. Core Technical Stack:

Layer	Technology
Frontend	Next.js 15 (App Router) + Tailwind CSS
Backend	Serverless API Routes (Next.js Edge Functions)
Auth	Supabase Auth with session context provider
Database	Supabase PostgreSQL (EU region)
AI/ML	OpenAI Whisper API (transcription), DeepL API (translation)
CI/CD	Local development + Netlify Deploy Hooks (staged)
Dev Tools	VS Code, GitHub Copilot, CodeSandbox

4. Key Architectural Benefits:

    Serverless: Auto-scaled Next.js API endpoints with zero backend maintenance

    Modular: Decoupled components (Supabase, Whisper, DeepL) for extensibility

    Privacy-First: No third-party tracking; all processing is handled client-side or via temporary in-memory API interactions — no user files are stored.

    Scalable: Built for linear expansion in user tiers, roles, and services

    Extensible: Stripe + Resend integrations scaffolded and config-ready


5. Compliance & Data Sovereignty:

    All user data and services hosted in GDPR-compliant EU regions

    No behavioral analytics or external cookie injection

    Role-based Row-Level Security (RLS) policies enforced via Supabase

    Email logic (password reset, notifications) pre-wired using Resend templates


6. Infrastructure Status:

Module	Status:

Supabase Auth	✅ Configured

Whisper Integration	✅ Complete

DeepL Integration	✅ Complete

Stripe Integration	🔜 Pending (Ireland LTD)

Email (Resend)	🔜 Scaffolded

CI/CD Hooks	🔜 To be finalized


7. Roadmap:

    Add Resend-powered transactional email + contact system

    Complete Stripe onboarding and launch tiered billing

    Optional: Offline/portable deployment support (for NGOs, field ops)

    Add opt-in usage metering with role-based quotas and RLS gating


8. Intellectual Property:

    Custom MVP SaaS architecture (Next.js + Supabase)

    AI pipeline integrations (Whisper/DeepL modules) authored internally

    Usage + billing scaffolding (internal logic) fully owned

    All frontend/backend logic and API integrations are original builds


        Per IP Licensing Agreement and Royalty Certificate, all MVP logic and integrations are authored and licensed by EcoNexus Systems OÜ with enforceable perpetual royalty rights.
   


10. Points of Contact:

    Email: admin@econexus.eu

    Representative: Rex Dale Black Jr

    Registry: EcoNexus OÜ (Estonia)

    Irish LTD (Billing Jurisdiction): In formation


11. Appendices (Available on Request):

    Screenshots of MVP dashboards and upload UI

    Stripe-ready config for usage tiers and limits

    Infrastructure diagrams + system flowcharts

    Founder contribution logs + valuation reports
