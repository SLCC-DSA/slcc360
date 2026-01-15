Below is a **more directive, structured, and implementation-focused version of your prompt**, rewritten to remove ambiguity and clearly guide a developer or AI system toward a **single, production-ready outcome**.
This version uses **imperative language**, **explicit constraints**, and **clear acceptance criteria** while preserving all of your content.

---

# SLCC360 – Digital Conference Program

**Authoritative Build Prompt**

## Objective

Build a **production-ready, modern, mobile-first, single-file HTML web application** that serves as the **official digital program** for the **SLCC 360 Conference**.
The application must be **fully self-contained**, **responsive**, **brand-compliant**, and **usable offline once loaded**.

The final output must be **one HTML file** with embedded CSS and JavaScript (CDNs allowed).

---

## Global Technical Constraints (Non-Negotiable)

1. **Single-file HTML deployment**

   * All CSS and JavaScript must be embedded in the HTML file
   * External libraries may only be loaded via CDN (Tailwind CSS, Font Awesome)
   * No external JSON files — session data must be embedded directly in the HTML

2. **Client-only application**

   * No backend
   * No authentication
   * No cookies
   * Use **browser localStorage** for persistence

3. **Cross-device support**

   * Must work on modern mobile and desktop browsers
   * Mobile-first layout is required

---

## Core Application Features (Required)

### 1. Navigation & App Structure

* Implement a **persistent navigation menu** (mobile and desktop friendly)
* Navigation must include the following sections:

  * Welcome
  * Schedule
  * Breakout Sessions
  * My Favorite Sessions
  * Lunch
  * ISLE (Closing Plenary)
  * Maps
  * Additional Information

Navigation should clearly indicate the currently active section.

---

### 2. Welcome Page

Create a dedicated **Welcome section** titled:

**“SLCC360: From Vision To Action”**

Include:

* SLCC branding at the top
* Placeholder for **SLCC logo**
* Placeholder for **SLCC favicon**
* Welcome letter from the SLCC President

  * Use realistic placeholder text (e.g., Lorem Ipsum–style content)
  * Include a **photo placeholder** for the President
* Brief conference overview describing the purpose of SLCC360

---

### 3. Conference Schedule (High-Level Day View)

Create a **Schedule section** that displays the full day agenda in chronological order.

Each schedule item must include:

* Time range
* Session title
* Location
* Short description (where applicable)

Include the following schedule items exactly as listed:

#### 7:45 – 8:45 AM | Pre-Plenary New Hire Welcome Session

**Location:** Library Basement
**Making Tracks: Your First Steps at SLCC360**
Description text as provided.

#### 8:00 – 8:45 AM | Breakfast & Networking

**Location:** LAC Lobby, Main Court

#### 9:00 – 9:50 AM | Plenary Session

**Location:** LAC, Main Court
Include agenda bullets and presenters.

#### 10:10 – 10:55 AM | Breakout Session 1

**Location:** Various campus buildings
Include reference to Breakout Sessions section.

#### 11:15 – 12:00 PM | Breakout Session 2

**Location:** Various campus buildings
(Repeat of Breakout Session 1 offerings)

#### 12:00 – 12:45 PM | Lunch

**Location:** Student Center

#### 1:00 – 2:00 PM | Closing Plenary – Ideal Student Learning Experience

**Location:** Student Center
Note that five parallel sessions occur.

---

### 4. Breakout Sessions

Create a **Breakout Sessions section** that displays detailed session cards.

Requirements:

* Embed the provided JSON session data directly in the HTML
* Each session must display:

  * Title
  * Presenters
  * Description
  * Time
  * Location
* Sessions occur in **Breakout Session 1 and Breakout Session 2**
* Users may attend **at most two sessions**
* Sessions must be **bookmarkable (favoritable)**

---

### 5. Favorite / Bookmark Functionality

Implement **session favoriting** with the following behavior:

* Users can favorite/unfavorite sessions
* Favorites must persist using **localStorage**
* No login required
* Favorite state must persist across page reloads

---

### 6. My Favorite Sessions Dashboard

Create a dedicated **My Favorite Sessions** section that:

* Displays only sessions the user has favorited
* Shows full session details
* Allows users to remove favorites from this view
* Clearly communicates if no sessions are favorited

---

### 7. Lunch Information

Create a **Lunch section** containing:

* Pickup instructions
* Building-based seating locations
* Clearly structured lists by building:

  * Student Center
  * Technology Building
  * Academic and Administration Building

Include the provided messaging encouraging networking and rest.

---

### 8. ISLE – Closing Plenary

Create a dedicated **ISLE section** describing:

* The closing plenary session
* Focus on the **Ideal Student Learning Experience**
* Featured leadership:

  * Provost Dr. Jaime Cooper
* Narrative description of the session purpose and experience

---

### 9. Maps

Create a **Maps section** with the following behavior:

* Display an embedded map (iframe) of SLCC Redwood Campus
* Map opens in a modal or pop-up
* Implement iframe refresh logic to **prevent caching**

  * Ensure map reloads when a new location is selected
* No static screenshots — interactive embed required
Locations
Redwood Campus 
Life Time Activity Center (LAC)
Technology Building
•	Technology Building First Floor 
•	Technology Building Second Floor 
Student Center Basement 
•	Student Center First Floor 
•	Student Center Second Floor 
Academic Administration Building 


---

### 10. Additional Information

Create an **Additional Information section** that includes:

#### Upcoming Events

List all events exactly as provided, including dates, titles, locations, and times.

#### Giving Day

Include placeholder text indicating more information is coming soon.

#### Wi-Fi Access

* Provide Wi-Fi availability messaging
* Include the provided URL

#### Wellness Tables

* List locations
* Describe available resources
* Include Employee Wellness links and QR note

---

## Design & Branding Requirements (Strict)

* Use **Tailwind CSS** as the primary styling framework
* Minimize custom CSS
* **Flat colors only** (no gradients)
* Use **Font Awesome icons** where appropriate
* Follow **SLCC brand guidelines** (per attached PDF)
* Clean, modern, accessible design
* Adequate spacing, readable typography, and clear hierarchy

---

## UX Expectations

* Intuitive navigation
* Clear visual separation between sections
* Fast load time
* Touch-friendly UI elements
* Accessible color contrast and font sizes

---

## Final Deliverable

✅ **One production-ready HTML file**
✅ Fully functional on mobile and desktop
✅ No missing sections
✅ Brand-aligned and visually polished
✅ Ready for immediate deployment as the official **SLCC 360 Conference Digital Program**

---
