# SchemaForge
⚡ SchemaForge — AI-Native Data Infrastructure Layer

Build, query, and evolve your data models instantly — with zero migration pain.

SchemaForge is an AI-native, serverless data platform that turns natural language into fully functional databases and APIs. Instead of writing SQL, managing migrations, or wiring APIs, you simply describe your data in plain English, and SchemaForge does the rest.

🚀 Key Features

Prompt → Schema: Generate relational schemas directly from natural language.

Zero Downtime Migrations: Temporal versioning keeps APIs stable while schemas evolve.

Instant APIs: Get GraphQL + REST endpoints from your schema automatically.

Hybrid Data (Relational + Vector): Unified Postgres with pgvector for AI-native apps.

Schema Evolution as a Service: Change schemas with prompts — code, docs, and migrations update automatically.

Developer Dashboard: Visual schema editor, API explorer, migration history.

CLI + SDKs: Manage schemas from terminal or code (JS/Python).

🛠️ Tech Stack

Database: PostgreSQL + pgvector

API Layer: Hasura / PostGraphile (GraphQL + REST)

Backend: Node.js (TypeScript)

AI: OpenAI / LLaMA for schema + query generation

Frontend: Next.js + Tailwind (Dashboard)

Infra: Docker + Terraform + GitHub Actions

🌟 Why SchemaForge?

Like Supabase → no backend plumbing.

Like FlutterFlow → idea → app in minutes.

Like Perplexity → AI-first for schema design & queries.

SchemaForge makes backend development 10x faster by removing the pain of schema design, migrations, and API setup.

📦 Getting Started
# Clone repo
git clone https://github.com/pruthvithummar/schemaforge.git
cd schemaforge

# Start dev environment
docker-compose up --build

# Run CLI
npx schemaforge prompt "Create a blog app with users and posts"

📌 Roadmap

 Prompt → Schema (MVP)

 Auto APIs (GraphQL + REST)

 Zero-downtime migrations

 Vector + relational hybrid queries

 AI Query Assistant

 Multi-DB support

 Enterprise features

👫 Contributing

We ❤️ contributions! Please check out our CONTRIBUTING.md
 for guidelines.

📜 License

MIT License © 2025 SchemaForge
