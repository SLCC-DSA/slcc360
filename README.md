# slcc360
A Repo to create and maintain a digital program for SLCC 360 Conference. 

### Prompt to Create

**Create a modern, responsive HTML web application for the SLCC 360 Conference program** that combines the following requirements:

## Core Features & Functionality
- **Welcome page** with SLCC branding and conference overview.
- **Program sections** displaying sessions with title, presenters, description, time, and location
- **Favorite/bookmark functionality** allowing users to save sessions without login using browser local storage
- **Favorites dashboard** showing all favorited sessions in one dedicated view
- **Mobile-optimized responsive design** working seamlessly on both mobile and desktop devices
- **Fully encapsulated HTML file** single-file deployment with embedded CSS and JavaScript.

## Design & Styling Requirements
- **Tailwind CSS** as primary styling framework (minimize custom inline CSS)
- **SLCC Brand Guidelines compliance** apply institutional styling as specified in attached guidelines document scc-brand-guideline-06-2017.pdf
- **Flat colors only** Do not use gradient colors. 
- **Font Awesome icons** for visual engagement use icons
- **Modern, engaging, visually appealing** ensure that the web application is visually appealing. 
- **SLCC logo** leave a placehoder for the SLCC logo
- **SLCC favicon** leave a placeholder for the SLCC favicon

# Content Requirements
### Welcome Page
- This is a page or section titled "SLCC360: From Vision To Action". The welcome page/section will have a welcome letter from the president, with a placeholder for a photo of the president. Use random text of the letter placehodler if needed. 

### Conference Schedule 
- This is a high level Conference Schedule for the day page or section
#### 7:45 – 8:45 AM | Pre-Plenary New Hire Welcome Session
- **Location:** Library Basement  
**Making Tracks: Your First Steps at SLCC360**  
Start your SLCC360 adventure on the right paw! If you’re in your first year and new to this event, join us in the Library Basement outside the Testing Center for a one-stop shop. Pick up your nametag, enjoy breakfast, and take part in a fun, welcoming session with tips to help you make tracks toward strategic planning.
---
#### 8:00 – 8:45 AM | Breakfast & Networking
- **Location:** LAC Lobby, Main Court  
---
#### 9:00 – 9:50 AM | Plenary Session
- **Location:** LAC, Main Court  
**Plenary Agenda:**
- **Welcome:** Brandi Mair, Chief of Staff  
- **Opening Remarks:** Greg Peterson, President  
- **Ideal Student Learning Experience Update:** Jamie Cooper, Provost  
- **Framing the Day:** Brandi Mair  
---
#### 10:10 – 10:55 AM | Breakout Session 1
- **Location:** Various buildings across campus  
  *(See Breakout Sessions for more details)*
---
#### 11:15 – 12:00 PM | Breakout Session 2  
*(Repeat of breakout sessions)*
- **Location:** Various buildings across campus  
  *(See Breakout Sessions for more details)*
---
#### 12:00 – 12:45 PM | Lunch
- **Location:** Student Center  
---
#### 1:00 – 2:00 PM | Closing Plenary: Ideal Student Learning Experience
- **Location:** Student Center  
- Five parallel sessions in various locations throughout the Student Center.

### Breakout Sessiosn
- Include a page or sesction to display complete session details: title, presenters, description, time, location. See attached json file for section details. Embbed the json file within the emcapuslated HTML file. The sessions wll occur in the conference schedule breakout sessions 1 and 2 to allow participants to attend at most two distinct sessions. 

### My Favorite Sessions
- Include a page or section to track the sessions that participatns have favorited for quick access.

### Lunch
- Inlcude a Page or Section for information on Luch. See Lunch section below for details. 
After the second breakout session ends, boxed lunches will be available for pickup in the **Student Center**. Seating is available in the following locations:
#### Student Center
- Food Court (main level)
- Student Event Center (main level)
- Oak Room (2nd Floor)
- Corner Room #219 (2nd Floor)
- Rooms 221/223 (2nd Floor)
- Rooms 207/213 (2nd Floor)
- Den 1 and 2 (basement)
- Senate Room 030 (basement)

#### Technology Building
- Professional Development Center (2nd Floor)

#### Academic and Administration Building
- Classroom 135
- Classroom 235

Take a break, enjoy your meal, and connect with colleagues before the final session!

### ISLE
- Include a page or session for the closing plenary. The closing plenary is a unique session featureing SLCC's Provost Dr. Jaime Cooper and others unveling and walking the audiance thorugh the SLCC Ideal Student Learning Experience.

### Maps
- Include a page or section with SLCC Redwood Campus locations, this can be called "Maps". This will be a embedded maps that can be displayed on a pop up. We wil using an iframe but needt to configure the iframe refresh such that no caching is is created so that if a new location is opened it refreshes accordingly. 

### Additional Information
- Include a page or section with additional information. 
#### Upcoming Events
- **February 27, 2026** | *Beloved Community Events*  
  South City Campus • 6:00–9:00 PM
- **March 24, 2026** | *Community Conversations – Olympic Speedskating Athletes*  
  STC Oak Room • 12:00–1:00 PM
- **March 26, 2026** | *Big Questions Forum – Alok*  
  Location TBD
- **April 24, 2026** | *Employee Recognition*  
  Jordan Campus • 9:00 AM–2:00 PM
- **May 8, 2026** | *Commencement*  
  Maverik Center • 10:00 AM–12:00 PM
#### Giving Day
More details coming soon. Stay tuned for ways to support and celebrate SLCC’s Giving Day.
#### Wi-Fi Access
Wi-Fi is available throughout the SLCC Redwood Campus.  
For connection help, visit the Student Technology Guide:  
https://slcc.edu/student-tech-guide/wifi-help.aspx

#### Wellness Tables
Recharge between breakout sessions at one of our **Wellness Stations**, located in:
- Student Center  
- Academic and Administration Building (AAB) Lobby  
- Technology Building (TB) Lobby  

Stop by for healthy snacks, flavored water packets, and resources on SLCC’s Employee Wellness programs. Team members will be available to answer questions and share tips to help you meet your wellness goals.

- **Employee Wellness Site:** https://i.slcc.edu/culture/wellness/index.aspx  
- **Employee Wellness QR Code:** Available on-site

## Technical Requirements
- **Single-file HTML** application (no external dependencies except CDNs)
- **Local storage persistence** for favorite sessions across page reloads
- **Navigation menu** with clear sections (Welcome, Program/Schedule, Breakout Sessions, Favorites)
- **Responsive grid/layout** adapting to different screen sizes
- **User-friendly, intuitive interface** prioritizing ease of use

**Deliverable:** A polished, production-ready HTML file ready for server deployment at SLCC that serves as the official SLCC 360 Conference program for attendees.