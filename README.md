# F1-Analytics-Dashboard

A data-driven single-page application built with React that visualizes Formula 1 seasons, race results, standings, and entity-level details using a relational PostgreSQL backend via Supabase.

This project was designed to simulate an operational analytics dashboard, integrating structured datasets and dynamic UI state management in a modular frontend architecture.

# Tech Stack

Frontend: React (Hooks, Functional Components), React Router

Backend/Data: Supabase (PostgreSQL)

Architecture: Single Page Application (SPA) using Vite

State Management: React useState, useEffect

Data Access: Supabase client queries (relational filtering, ordering, joins)

Routing: Dynamic route parameters (/race-results/:raceId, /race-standings/:raceId)

# Features

Season selector (2000–2023) with dynamic race filtering

Race results and qualifying data views

Driver and constructor standings per race

Modular detail modals for:

Drivers

Constructors

Circuits

Favorites system with deduplication logic and centralized state handling

Conditional rendering for empty-state UX

Asynchronous data fetching with error handling

Route-based rendering and dynamic navigation flows

# Data Model

The application integrates relational data across multiple structured tables:

Seasons

Races

Results

Qualifying

Drivers

Constructors

Circuits

Relational joins and filtered queries are executed through Supabase to ensure efficient and scoped data retrieval.
