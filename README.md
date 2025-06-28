# alx-graphql-0x02
markdown
# ALX Rick and Morty GraphQL App

This project is a React-based frontend built with **Next.js**, **TypeScript**, **TailwindCSS**, and **Apollo Client**. It consumes the [Rick and Morty GraphQL API](https://rickandmortyapi.com/graphql) to display episodes with pagination.

---

##  Project Structure

This repo reflects two progressive phases:

- **0x01** – Set up project structure, GraphQL client, and environment
- **0x02** – Fetch and render paginated data using Apollo `useQuery`, dynamic state, and reusable components

---

##  Technologies Used

- [Next.js](https://nextjs.org/) (App framework)
- [TypeScript](https://www.typescriptlang.org/) (Type safety)
- [Tailwind CSS](https://tailwindcss.com/) (Styling)
- [Apollo Client](https://www.apollographql.com/docs/react/) (GraphQL queries)
- [GraphQL](https://graphql.org/) (API layer)

---

##  Installation & Setup

```bash
git clone https://github.com/Peter-Adjao/alx-graphql-0x02.git
cd alx-graphql-0x02/alx-rick-and-morty-app

npm install
npm run dev
Open your browser to http://localhost:3000

 Project Features
✅ Apollo Client Setup (graphql/apolloClient.ts)
Configured Apollo Client with HTTP link and in-memory cache

Connected to https://rickandmortyapi.com/graphql

✅ Episode Query Setup (graphql/queries.ts)
Defined GET_EPISODES query with pagination and filters

✅ Global Apollo Provider (pages/_app.tsx)
Wrapped the app using <ApolloProvider> to enable query access

✅ Data Interfaces (interfaces/index.ts)
Created TypeScript interfaces for episode data structure and props

✅ Episode UI + Pagination (pages/index.tsx)
Queried episode data using useQuery

Rendered episodes using custom EpisodeCard component

Implemented pagination logic with useState and useEffect

 UI Highlights
Responsive episode grid

Gradient-themed layout with TailwindCSS

Pagination buttons with smooth hover effects

Reusable EpisodeCard for cleaner structure

 Learning Objectives
Initialize a TypeScript-ready Next.js project with Tailwind and ESLint

Integrate Apollo Client and perform queries against a GraphQL endpoint

Handle query variables, pagination, and dynamic re-fetching

Use modular React components and custom interfaces for type safety

📂 File Structure
alx-rick-and-morty-app/
├── graphql/
│   ├── apolloClient.ts
│   └── queries.ts
├── interfaces/
│   └── index.ts
├── components/
│   └── common/
│       └── EpisodeCard.tsx
├── pages/
│   ├── _app.tsx
│   └── index.tsx
├── styles/
│   └── globals.css
└── tsconfig.json
 Author
Peter Adjao GitHub: @Peter-Adjao
