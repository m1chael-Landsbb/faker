# Coalition Systems: Resource Rally

Welcome to the official repository for **Coalition Systems: Resource Rally**, a cyberpunk themed incremental automation game built with Svelte and integrated with Supabase. Lead humanity's recovery from corporate collapse by optimizing your operations, upgrading your facility, and competing on a global scale.

## 🚀 Game Concept

In a post-corporate future, humanity must rebuild from the ruins of the fallen MegaCorp Syndicate. As an Operations Director in the Coalition, your mission is to gather critical resources to construct massive RecoveryHub Stations and guide your faction to prosperity in the NeoUrban sectors.

This game is an "automate-to-progress" experience where players advance through cycles, complete objectives, and climb the rankings.

## ✨ Core Features

- **Automate-to-Progress Gameplay:** The core mechanic involves optimizing automation systems to generate resources and advance.
- **Player Progression System:**
  - **Tiers & Points:** Earn points with every cycle, advance tiers, and unlock new director titles.
  - **Dynamic Status Colors:** The UI and facility's interface visually evolve with player tier, changing colors at major thresholds.
- **Upgrades & Optimization:**
  - **Director Upgrades:** Spend resources to enhance production rate, efficiency multipliers, automation bonuses, and more.
  - **Station Bay:** Connect a (simulated) blockchain wallet to unlock and acquire exclusive Station upgrades.
- **Passive Generation with A.U.T.O. Units:** Purchase A.U.T.O. Units that passively generate resources for you while you're offline.
- **In-Game Economy:**
  - **Dual Currency:** Earn **Resources** through gameplay and use **Credits** (premium currency) for special items.
  - **Supply Depot:** Purchase temporary production boosts and other buffs using Credits.
- **Advancement Track System:**
  - Progress through a seasonal Advancement Track by earning points.
  - Includes both **free and premium** reward tracks.
  - Unlock exclusive interfaces, titles, currency, and buffs.
- **V.I.R.A. AI Assistant (Genkit Powered):**
  - An AI-powered assistant that provides dynamic operation briefings, adaptive optimization advice, and immersive lore snippets based on player progress.
- **Social & Community Features:**
  - **Global Rankings:** Compete with players worldwide for the top position.
  - **Coalition Network:** A simulated network hub to coordinate with fellow directors.
  - **Feedback & Support Forms:** Integrated pages for players to submit feedback or contact support.
- **Daily Objectives:** Complete daily tasks to earn valuable rewards and accelerate your progress.
- **Blockchain Integration (Simulated):**
  - A "Connect Wallet" feature that rewards players with Credits and unlocks special game content.
  - A comprehensive **Transparency Statement** page explaining the role of digital assets.

## 💻 Tech Stack

- **Framework:** [SvelteKit](https://kit.svelte.dev/)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [TailwindCSS](https://tailwindcss.com/)
- **UI Components:** [Skeleton UI](https://www.skeleton.dev/)
- **Generative AI:** [Firebase Genkit](https://firebase.google.com/docs/genkit)
- **Deployment:** [Supabase Hosting](https://supabase.com/docs/guides/hosting)

## 🛠️ Getting Started

To run the project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/coalitionsystems/resourcerally.git
    cd resourcerally
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Run the development server:**
    ```bash
    npm run dev
    ```

4.  Open [http://localhost:5173](http://localhost:5173) in your browser to see the application.

## 📂 Project Structure

- `src/routes/`: Contains all the pages and routes for the application.
- `src/lib/components/`: Shared Svelte components used across different pages (e.g., layout, UI elements, game components).
- `src/lib/stores/`: Home of the game state management, which manages all global game state and logic.
- `src/lib/data/`: Core game data definitions, type declarations, and utility functions.
- `src/lib/ai/`: Holds all the Genkit-related code, including flows for the V.I.R.A. AI assistant.
- `static/`: Static assets like images and sounds.

## ☁️ Deployment

This project is configured for seamless deployment using **Supabase Hosting**. The hosting configuration defines the deployment settings.

The deployment process is automated via GitHub Actions:
1.  Push your code changes to the `main` branch of your GitHub repository.
2.  Supabase Hosting automatically detects the push, builds the SvelteKit application, and deploys it.
3.  The live URL will be available in your Supabase project's Hosting dashboard, which is `https://resource-rally.supabase.co`.

# resource-rally-CS
