
## How Buildings Work

| Metric         | Affects           | Example                                |
|----------------|-------------------|----------------------------------------|
| Contributions  | Building height   | 1,000 commits → taller building        |
| Public repos   | Building width    | More repos → wider base                |
| Stars          | Window brightness | More stars → more lit windows           |
| Activity       | Window pattern    | Recent activity → distinct glow pattern |



- **Framework:** [Next.js](https://nextjs.org) 16 (App Router, Turbopack)
- **3D Engine:** [Three.js](https://threejs.org) via [@react-three/fiber](https://github.com/pmndrs/react-three-fiber) + [drei](https://github.com/pmndrs/drei)
- **Database & Auth:** [Supabase](https://supabase.com) (PostgreSQL, GitHub OAuth, Row Level Security)
- **Payments:** [Stripe](https://stripe.com)
- **Styling:** [Tailwind CSS](https://tailwindcss.com) v4 with pixel font (Silkscreen)
- **Hosting:** [Vercel](https://vercel.com)

## Getting Started

```bash
# Clone the repo
git clone https://github.com/srizzon/git-city.git
cd git-city

# Install dependencies
npm install

# Set up environment variables

# Linux / macOS
cp .env.example .env.local

# Windows (Command Prompt)
copy .env.example .env.local

# Windows (PowerShell)
Copy-Item .env.example .env.local

# Fill in Supabase and Stripe keys

# Run the dev server
npm run dev
```

Open [http://localhost:3001](http://localhost:3001) to see the city.

## License

[AGPL-3.0](LICENSE) — You can use and modify Git City, but any public deployment must share the source code.

---


