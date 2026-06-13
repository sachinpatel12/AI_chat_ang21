# AI Developer Assistant - Project Blueprint (Angular 21)

## Goal

Build a frontend-only Angular 21 application that teaches almost every important Angular concept through a real-world project.

The application will help developers:

* Chat with AI (mock initially)
* Save prompts
* Search developer resources
* Use developer tools
* Manage conversations
* Explore APIs

Backend is NOT required initially.

Data Sources:

* LocalStorage
* Signals
* Public APIs

Future Upgrades:

* Node.js Backend
* MongoDB
* Authentication
* OpenRouter / Gemini / OpenAI

---

# Application Layout

Application consists of:

1. Sidebar
2. Top Navbar
3. Main Content Area
4. Dialog System
5. Notification System

---

# Pages

## 1. Dashboard Page

Route:

/dashboard

Purpose:

Landing page after opening app.

Widgets:

* Total Chats
* Saved Prompts
* Favorite Prompts
* Recent Conversations
* Quick Actions

Buttons:

* New Chat
* Open Prompt Library
* API Explorer
* Settings

Angular Concepts:

* Standalone Components
* Signals
* Computed Signals
* @for
* @if
* Card Components

---

## 2. Chat Page

Route:

/chat/:id

Purpose:

Main AI conversation page.

Sections:

Left:

* Chat History

Center:

* Messages

Bottom:

* Message Input

Buttons:

* Send
* New Chat
* Delete Chat
* Export Chat
* Favorite Chat

Angular Concepts:

* Reactive Forms
* Validators
* HttpClient
* Observables
* Signals
* Pipes
* Dynamic Routing

---

## 3. Prompt Library

Route:

/prompts

Purpose:

Store reusable prompts.

Features:

* Search Prompt
* Add Prompt
* Edit Prompt
* Delete Prompt
* Favorite Prompt

Buttons:

* Add Prompt
* Save
* Cancel
* Delete

Angular Concepts:

* CRUD
* Reactive Forms
* FormArray
* Search Filters
* Custom Pipes

---

## 4. API Explorer

Route:

/api-explorer

Purpose:

Practice real APIs.

Modules:

* Weather
* Dictionary
* Country Search
* Movie Search

Buttons:

* Search
* Clear

Angular Concepts:

* HttpClient
* switchMap
* debounceTime
* distinctUntilChanged
* Error Handling

---

## 5. Settings Page

Route:

/settings

Features:

* Dark Mode
* Font Size
* Language
* Default AI Model

Buttons:

* Save
* Reset

Angular Concepts:

* Signals
* Effects
* LocalStorage

---

## 6. Profile Page

Route:

/profile

Features:

* Username
* Experience Level
* Preferred Stack

Buttons:

* Edit
* Save

Angular Concepts:

* Reactive Forms
* Reusable Components

---

## 7. Favorites Page

Route:

/favorites

Purpose:

View favorite prompts and chats.

Angular Concepts:

* State Management
* Computed Signals

---

# Reusable Components

## Sidebar Component

Items:

* Dashboard
* Chat
* Prompt Library
* API Explorer
* Favorites
* Settings

Concepts:

* Routing
* RouterLinkActive

---

## Navbar Component

Items:

* Search
* Notifications
* Profile

Concepts:

* Input/Output
* Shared Components

---

## Chat Message Component

Types:

* Text
* Code
* Image
* Markdown

Concepts:

* Dynamic Components

---

## Modal Component

Used For:

* Add Prompt
* Edit Prompt
* Confirm Delete

Concepts:

* Dynamic Component Creation
* ViewContainerRef

---

## Notification Component

Used For:

* Success
* Error
* Warning

Concepts:

* Subject
* BehaviorSubject

---

# Angular Concepts Learning Roadmap

Phase 1

* Components
* Standalone Components
* Routing
* Layout

Pages Built:

Dashboard
Sidebar
Navbar

---

Phase 2

* Reactive Forms
* Validators
* Custom Pipes

Pages Built:

Prompt Library

---

Phase 3

* HttpClient
* Observables
* Services

Pages Built:

API Explorer

---

Phase 4

* Subject
* BehaviorSubject
* ReplaySubject

Features Built:

Notifications
Shared State

---

Phase 5

* RxJS Operators

Operators:

* switchMap
* debounceTime
* distinctUntilChanged
* combineLatest
* forkJoin

Pages Built:

Search Features
API Explorer

---

Phase 6

* Signals
* Computed
* Effects

Pages Built:

Dashboard
Settings

---

Phase 7

* Dynamic Components

Features Built:

Chat Messages
Modals

---

Phase 8

* Advanced Features

Features:

* Export Chat
* Theme Management
* Caching
* Error Handling

---

# Total Screens

1. Dashboard
2. Chat
3. Prompt Library
4. API Explorer
5. Favorites
6. Settings
7. Profile

Total Main Pages = 7

Total Reusable Components = 10+

Total Angular Concepts Covered = 90%+
