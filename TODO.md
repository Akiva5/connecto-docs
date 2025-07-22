# Connecto To-Do List

This list tracks the immediate, high-priority tasks for the current development phase.

## Phase 1: Build the Engine

-   [ ] **Set up `connecto-backend` Repository:**
    -   [ ] Initialize a new Node.js project.
    -   [ ] Set up Firebase Admin SDK.
    -   [ ] Configure for Firebase Functions deployment.
-   [ ] **Develop First Sync Function (`indexGoogleDrive`):**
    -   [ ] Implement Google Drive API OAuth flow for a server-side application.
    -   [ ] Create a Firebase Function that fetches the last 20 file names from a connected Google Drive account.
    -   [ ] Write the fetched file metadata (name, link, date) to a Firestore collection.
-   [ ] **Create Test Script:**
    -   [ ] Write a local Node.js script (`test-drive-sync.js`) to invoke the `indexGoogleDrive` function.
    -   [ ] Verify that running the script populates Firestore as expected.
-   [ ] **Develop First Search Endpoint:**
    -   [ ] Create a simple HTTP-triggered Firebase Function (`search`) that can query the indexed data in Firestore.
