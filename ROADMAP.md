# Connecto Project Roadmap

This document outlines the development strategy and phased roadmap for Connecto, following the "Engine First" approach.

## Core Strategy: The Two-Layer System

Connecto is being built as two distinct but connected layers:

1.  **The Connecto Engine (Backend):** A powerful, API-driven backend built with Firebase Functions. It has no UI and handles all core logic: data connections, syncing, indexing, and searching. This layer serves as the powerful personal tool.
2.  **The Connecto App (Frontend):** A user-friendly Next.js web application that acts as a client to the Engine. Its sole purpose is to provide an intuitive interface for users to interact with the data managed by the Engine.

This approach allows for rapid backend development while ensuring the core logic is robust and independent of the user interface.

---

## Phase 1: Build the Engine (The Personal Tool)

* **Goal:** Create a functional backend that can connect to services, sync data, and be controlled via scripts.
* **Focus:** 100% backend development in the `connecto-backend` repository. No UI work.
* **Key Milestone:** Successfully sync data from a service (e.g., Google Drive) into Firestore and retrieve it with a simple script.

## Phase 2: Build the App (The Business Product)

* **Goal:** Create the initial user-facing application.
* **Focus:** Frontend development in the `connecto-frontend` repository, connecting to the already-built Engine APIs.
* **Key Milestone:** Display data fetched from the Engine on a simple, clean web interface.

## Phase 3: Expand and Refine

* **Goal:** Add more service integrations to the Engine and build out corresponding UI components in the App.
* **Focus:** Iterative development across both backend and frontend, based on user feedback and strategic priorities.
