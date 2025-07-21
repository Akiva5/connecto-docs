# Connecto - Figma Prototype Requirements

## 1. Overall Goal
To create a low-fidelity, clickable prototype that validates the core user journey of Connecto. The design must prioritize clarity, simplicity, and establishing user trust from the very first interaction.

### Design Principles:
 * **Clarity over Clutter:** Every element on the screen should have a clear purpose.
 * **Mobile-First:** Design for a mobile viewport first to ensure the layout is focused and scalable.
 * **Trust Through Transparency:** The user should always feel in control and informed about what is happening with their data.

## 2. Global Elements (To be present on most screens)
 * **Simple Navigation:** A persistent sidebar (on desktop) or bottom bar (on mobile) with links to:
   * Dashboard
   * Search
   * Connections / Settings
 * **Search Bar:** A prominent, easily accessible search bar, likely at the top of the page.
 * **User Profile/Account Icon:** An icon indicating the logged-in user.

## 3. Key Screens to Prototype

### Screen 1: Onboarding & First Connection
**Goal:** To get a new user to connect their first service (e.g., Google) with a feeling of security and confidence.

**Must-Have Elements:**
 * A clear welcome message explaining what Connecto does in one sentence.
 * A list of services that can be connected (e.g., Google Drive, Gmail, Notion), each with its logo.
 * A primary "Connect Google Account" button.

**User Actions to Prototype:**
 * User clicks "Connect Google Account."
 * A modal window (a pop-up) appears before redirecting to Google. This modal is crucial for building trust. It should clearly state:
   * "Connecto is requesting permission to..."
   * A simplified list of permissions needed (e.g., "View and search your file names," "Read email subjects and senders").
   * A reassurance: "We only read metadata for searching. We never store the content of your files or emails unless you explicitly save them."
   * A "Proceed to Google" button.

**Questions to Answer with Your Design:**
 * How do we make the user feel safe before they give us access to their data?
 * Is it obvious what the benefit of connecting an account is?

### Screen 2: The Dashboard
**Goal:** To provide a simple, at-a-glance overview of the user's digital world and the app's status.

**Must-Have Elements:**
 * A "Welcome back, [User Name]" greeting.
 * A section showing "Connected Services" with their icons and a status indicator (e.g., a green dot for "Synced," a yellow dot for "Syncing...").
 * A "Recent Activity" feed showing the latest items indexed (e.g., "New file: 'Project Proposal.docx'", "New email from: Miriam Seymour").
 * A button to "Add a new connection."

**Questions to Answer with Your Design:**
 * Does this screen feel calm and organized, or overwhelming?
 * Can the user understand the status of their data in 3 seconds or less?

### Screen 3: Search Interface & Results
**Goal:** To demonstrate the core "magic" of Connecto: finding anything, from anywhere, instantly.

**Must-Have Elements:**
 * A large, central search input field.
 * When search results are displayed:
   * Each result item should have an icon indicating its source (e.g., Google Drive icon, Gmail icon).
   * Each result should show a title, a brief snippet of content, and the date.
   * Filters (e.g., filter by service, by date, by file type).

**User Actions to Prototype:**
 * User types a query into the search bar.
 * The view changes to show a list of mock search results from different sources.
 * User clicks a filter (e.g., "Gmail").
 * The list updates to show only results from that source.

**Questions to Answer with Your Design:**
 * How do we clearly differentiate between results from different services?
 * Is it easy to understand and use the filters to narrow down results?
