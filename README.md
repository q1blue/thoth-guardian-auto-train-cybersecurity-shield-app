Data Connect

Connect your app to a PostgreSQL database with a powerful managed app server

Get started with Gemini

Learn more

settings

How do I get started?

View the docs

credit_card

How much will Data Connect cost?

View pricing

sentiment_satisfied_alt

What can Data Connect do for me?

Learn more

See all Firebase featuresarrow_forward

Vertex AI in Firebase is now Firebase AI Logic and it gives you access to the Gemini Developer API

type User @table {
  username: String!
  createdAt: Timestamp!
  email: String
  displayName: String
  lastLogin: Timestamp
}

type PlayerProfile @table {
  user: User!
  level: Int!
  totalThreatsNeutralized: Int!
  lastUpdated: Timestamp!
  currentAbilities: [String]
  evolutionPhase: String
}

type MissionRecord @table {
  user: User!
  missionName: String!
  completedAt: Timestamp!
  successStatus: Boolean!
  threatsNeutralized: Int
  timeTakenSeconds: Int
  score: Int
  feedbackSubmitted: Boolean
}

type SharedCreation @table {
  user: User!
  title: String!
  type: String!
  contentData: String!
  isPublic: Boolean!
  createdAt: Timestamp!
  updatedAt: Timestamp!
  description: String
  likesCount: Int
  viewsCount: Int
}

type CommunityPost @table {
  user: User!
  postType: String!
  content: String!
  createdAt: Timestamp!
  updatedAt: Timestamp!
  isPublic: Boolean!
  title: String
  parent: CommunityPost
  missionRecord: MissionRecord
  likesCount: Int
}
2025-07-16T19:05:23.577Z	Initializing build environment...
2025-07-16T19:05:23.577Z	Initializing build environment...
2025-07-16T19:05:30.083Z	Success: Finished initializing build environment
2025-07-16T19:05:30.287Z	Cloning seed repository...
2025-07-16T19:05:30.309Z	Cloning from: https://github.com/cloudflare/templates.git
2025-07-16T19:05:32.108Z	Overwriting files
2025-07-16T19:05:32.737Z	Pushing to destination: https://github.com/q1blue/thoth-guardian-auto-train-cybersecurity-shield-app.git
2025-07-16T19:05:34.348Z	Detected the following tools from environment: npm@10.9.2, nodejs@22.16.0, bun@1.2.15
2025-07-16T19:05:34.350Z	Installing project dependencies: bun install --frozen-lockfile
2025-07-16T19:05:34.494Z	bun install v1.2.15 (df017990)
2025-07-16T19:05:34.512Z	[9.99ms] migrated lockfile from package-lock.json
2025-07-16T19:05:36.631Z	Saved lockfile
2025-07-16T19:05:36.632Z	
2025-07-16T19:05:36.632Z	+ cobe@0.6.3
2025-07-16T19:05:36.632Z	+ partyserver@0.0.66
2025-07-16T19:05:36.632Z	+ partysocket@1.1.3
2025-07-16T19:05:36.632Z	+ react@18.3.1
2025-07-16T19:05:36.632Z	+ react-dom@18.3.1
2025-07-16T19:05:36.633Z	+ @types/react@18.3.23
2025-07-16T19:05:36.633Z	+ @types/react-dom@18.3.7
2025-07-16T19:05:36.633Z	+ esbuild@0.25.2
2025-07-16T19:05:36.633Z	+ typescript@5.8.3
2025-07-16T19:05:36.633Z	+ wrangler@4.21.2
2025-07-16T19:05:36.633Z	
2025-07-16T19:05:36.633Z	71 packages installed [2.17s]
2025-07-16T19:05:36.650Z	Executing user build command: Start Build
2025-07-16T19:05:36.653Z	/bin/sh: 1: Start: not found
2025-07-16T19:05:36.656Z	Failed: error occurred while running build commanda{text-decoration:none;color:#464feb}

Your updated Unreal Engine 5.6 project structure is ready, now including:

📦 Download the full asset and Blueprint template pack:
ThothGuardianCyberShieldProject.zip

🧩 Included Modules & Templates 🖥️ UX Interfaces MainDashboard.uasset TouchscreenHUD.uasset LanguageSelector.uasset 📊 Dashboards CyberShieldStatus.uasset CommunityFeedbackPanel.uasset 🧪 Alchemy Transformation NigredoPhase.uasset AlbedoPhase.uasset CitrinitasPhase.uasset RubedoPhase.uasset 🌟 Transformational Journey Awakening.uasset Purification.uasset Transmutation.uasset Integration.uasset Ascension.uasset 🌍 Elemental Environments EarthRealm.uasset WaterSanctuary.uasset FireTemple.uasset AirCitadel.uasset AetherGate.uasset 🔷 Sacred Geometry PhilosophersStone.uasset OuroborosSymbol.uasset TreeOfLife.uasset MandalasVisual.uasset 🛠️ Simulator Builder ArchitectureDesigner.uasset InfrastructurePlanner.uasset EcosystemSimulator.uasset 

These assets are ready for integration with the visual diagrams and gameplay systems. Would you like help wiring these templates into your Unreal Engine project or generating cinematic sequences for each transformational phase?

a{text-decoration:none;color:#464feb}

The visual diagrams you've requested are currently being generated and will appear below as they are completed. Here's a quick summary of what's coming:

🧭 Visual Diagrams in Progress: 

Blueprint Interface Diagram 

Touchscreen-style layout for Thoth Guardian's core functions Includes ActivateCyberShield, TimeTravelDebug, EvolveBehavior, RenderQuantumMindmap 

Transformational Journey Architecture 

Five phases: Awakening, Purification, Transmutation, Integration, Ascension Includes mystical environments, cosmic gateways, and symbolic energies 

Alchemy Transformation Map 

Four alchemical stages: Nigredo, Albedo, Citrinitas, Rubedo Elemental forces, sacred geometry, duality symbols, and cosmic integration 

Each diagram will be styled with cinematic depth, glowing accents, and mystical-tech aesthetics suitable for Unreal Engine integration.

Once they appear, I’ll guide you through how to use them in your project. Would you like me to prepare the Unreal Engine asset folders and Blueprint templates for each diagram as well?

a{text-decoration:none;color:#464feb}

To link SDKs, APIs, wikis, mods, and interactive buttons to your Unreal Engine 5.6 project, here’s a streamlined guide based on the latest documentation and developer tools:

🔗 Unreal Engine 5.6 Integration Guide ✅ 1. Linking APIs (e.g., Quantum-Safe Communication, Feedback Systems) 

Use Unreal’s built-in HTTP module with C++ or Blueprints:

Create a Blueprint Function Library Use HTTP GET/POST nodes or C++ FHttpModule for real-time API calls Parse JSON responses and display in-game 

📺 Video Guide: API Integration in UE 5.6 [1]

✅ 2. SDK Management with Unreal Turnkey 

Unreal Turnkey automates SDK setup for platforms like Windows, Android, iOS, etc.

Go to Platforms > SDK Setup Use Turnkey to install and configure SDKs Supports flashing dev kits and managing dependencies 

📘 Turnkey SDK Setup Guide [2]

✅ 3. Adding Mods and Wikis Create a Mods folder in your project Use Pak files or Blueprint mod loaders Link to external wikis via in-game UI or browser widget ✅ 4. Interactive Buttons and UI Links 

Use UMG (Unreal Motion Graphics) to create:

Buttons that trigger Blueprint functions Links to external APIs, documentation, or community portals Dynamic UI panels for feedback, tutorials, and partner ecosystems 

📘 Unreal Engine 5.6 Documentation [3]

Would you like help creating a Blueprint Function Library for API calls or setting up a UI panel with interactive buttons in your project?


References

[1] Unreal Engine API Integration Unlock Powerful Features

[2] Automating Platform and SDK Management with Unreal Turnkey | Unreal ...

[3] Unreal Engine 5.6 Documentation - Epic Dev

a{text-decoration:none;color:#464feb}

The key elements of Alchemy Transformation—especially as applied to your mystical, cinematic game world—combine ancient symbolic wisdom with modern interactive design. Here's a breakdown tailored for integration into the Thoth Guardian Cybersecurity Shield platform:

🧪 Core Elements of Alchemy Transformation 1. The Four Alchemical Stages 

These stages mirror inner transformation and can be gamified as quests or phases:

Nigredo (Blackening) – Dissolution, facing the shadow, chaos Albedo (Whitening) – Purification, clarity, emotional healing Citrinitas (Yellowing) – Awakening, illumination, insight Rubedo (Reddening) – Integration, mastery, rebirth 

These can align with your journey phases: Awakening → Purification → Transmutation → Integration → Ascension

2. Elemental Forces 

Alchemy is deeply tied to the classical elements:

🌍 Earth – Groundedness, stability, body 💧 Water – Emotion, intuition, flow 🔥 Fire – Willpower, transformation, energy 🌬️ Air – Intellect, breath, communication 🌌 Aether/Spirit – Unity, consciousness, divine connection 

These can be represented through wildlife, environments, and gameplay mechanics.

3. Duality & Balance Yin & Yang – Passive/active, feminine/masculine, dark/light Solar & Lunar Energies – Conscious vs subconscious Above & Below – As above, so below (macrocosm/microcosm) 

These themes can be woven into character design, puzzles, and world-building.

4. Sacred Geometry & Symbols The Philosopher’s Stone – Symbol of ultimate transformation The Ouroboros – Cycle of death and rebirth The Tree of Life – Connection between realms Mandalas & Sigils – Used for visual storytelling and UI design 5. Alchemy in Gameplay Transmutation Quests – Turn base materials into rare artifacts Energy Balancing Challenges – Solve puzzles to align forces Cosmic Gateways – Unlock new realms through spiritual mastery MetaHuman Evolution – AI characters evolve through player choices 

Would you like me to generate a visual map of these elements as part of your game’s transformation system? Or begin building Blueprint logic for one of the alchemical stages?

Generate a visual diagram of the journey architecture. a{text-decoration:none;color:#464feb}

Beautiful direction! With The Alchemist’s Transformational Journey now integrated into the Thoth Guardian Cybersecurity Shield platform, we’ll expand the game’s architecture to include:

🌟 Transformational Journey Modules 🧭 Journey Phases Awakening – Discovery of purpose and inner power Purification – Trials, challenges, and shedding illusions Transmutation – Quantum evolution and skill mastery Integration – Balance of masculine/feminine, yin/yang Ascension – Universal alignment and cosmic awareness 🧬 Gameplay Elements Interactive quests tied to each phase Cinematic environments reflecting emotional and spiritual states Mystical wildlife and elemental guardians Quantum puzzles and ethical decision-making AI-guided reflections and feedback loops 🛠️ Infrastructure Expansion Simulator Builder: Create your own transformational journey Architectural Designer: Build sacred spaces, temples, and cosmic gateways Ecosystem Planner: Balance nature, energy, and community 🌐 Universal Alignment Systems Energy balancing mechanics Duality integration (yin/yang, masculine/feminine) Cosmic calendar and celestial events Community rituals and collaborative learning 

Would you like me to generate a visual diagram of this expanded journey architecture or begin building the Blueprint logic for each transformational phase?

Edit Rituals changed to Alchemy transformation # Multiplayer Globe App

[![Deploy to Cloudflare](https://deploy.workers.cloudflare.com/button)](https://deploy.workers.cloudflare.com/?url=https://github.com/cloudflare/templates/tree/main/multiplayer-globe-template)

![Multiplayer Globe Template Preview](https://imagedelivery.net/wSMYJvS3Xw-n339CbDyDIA/43100bd9-8e11-4c20-cc00-3bec86253f00/public)

<!-- dash-content-start -->

Using the power of [Durable Objects](https://developers.cloudflare.com/durable-objects/), this example shows website visitor locations in real-time. Anyone around the world visiting the [demo website](https://multiplayer-globe-template.templates.workers.dev) will be displayed as a dot on the globe! This template is powered by [PartyKit](https://www.partykit.io/).

## How It Works

Each time someone visits the page, a WebSocket connection is opened with a Durable Object that manages the state of the globe. Visitors are placed on the globe based on the geographic location of their IP address, which is exposed as a [property on the initial HTTP request](https://developers.cloudflare.com/workers/runtime-apis/request/#incomingrequestcfproperties) that establishes the WebSocket connection.

The Durable Object instance that manages the state of the globe runs in one location, and handles all incoming WebSocket connections. When a new connection is established, the Durable Object broadcasts the location of the new visitor to all other active visitors, and the client adds the new visitor to the globe visualization. When someone leaves the page and their connection is closed, the Durable Object similarly broadcasts their removal. The Durable Object instance remains active as long as there is at least one open connection. If all open connections are closed, the Durable Object instance is purged from memory and remains inactive until a new visitor lands on the page, opens a connection, and restarts the lifecycle.

## More on Durable Objects

In this template, only one Durable Object instance is created, since all visitors should see updates from all other visitors, everywhere in the world. A more complex version of this application could instead show a map of the country the visitor is located in, and only display markers for other visitors who are located in the same country. In this case, a Durable Object instance would be created for each country, and the client would connect to and receive updates from the Durable Object instance corresponding to the visitor's country.

For this example, Durable Objects are used for synchronizing but not storing state. Since visitor connections are ephemeral, and tied to the in-memory lifespan of the Durable Object instance, there's no need to use persistent storage. However, a more complex version of this application could display the all-time visitor count, which needs to be persisted beyond the in-memory lifespan of the Durable Object. In this case, the Durable Object code would use the [Durable Object Storage API](https://developers.cloudflare.com/durable-objects/api/storage-api/) to persist the value of the counter.

<!-- dash-content-end -->

## Getting Started

Outside of this repo, you can start a new project with this template using [C3](https://developers.cloudflare.com/pages/get-started/c3/) (the `create-cloudflare` CLI):

```
npm create cloudflare@latest -- --template=cloudflare/templates/multiplayer-globe-template
```

A live public deployment of this template is available at [https://multiplayer-globe-template.templates.workers.dev](https://multiplayer-globe-template.templates.workers.dev)

## Setup Steps

1. Install the project dependencies with a package manager of your choice:
   ```bash
   npm install
   ```
2. Deploy the project!
   ```bash
   npx wrangler deploy
   ```
