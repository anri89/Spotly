# **Spotly**

### Discover the vibe & Share your world 

A creative community map for students and young people in Bath

Spotly is a full stack web app that helps new students and young people discover the real Bath such as local cafes, pubs, study spots, events, and hidden gems shared by other students and locals



## **Concept**

When you move to a new city, it’s hard to know where the real vibe is the cool pubs, good coffee, cheap eats, or quiet places to read.
Spotly solves that by letting users share personal experiences, photos, and event updates through an interactive map

Each location is pinned with short reviews, vibe tags (like chill, lively, study spot), and user uploaded media.
The app builds a friendly, authentic community around exploring Bath together


## **Unique Features (Core Version)**

* Interactive map with user generated pins
* Posts with images, short videos, and text
* User accounts with personal “albums” of places
* Mood or vibe filter (e.g. chill, party, artsy, study)
* Comment, like, and share system
* Optional events or party invites for local connection


## **Future Features & Potential**

*(Stretch goals and creative extensions)*

* 3D Map Experience (Three.js)
  Explore Bath in a 3D interactive map, allowing users to “walk” through local streets and explore the vibe of areas virtually

* Friend Match System
  A smart feature that connects users who share similar interests or visit similar spots
  (e.g. “You and Ella both love The Bell Inn and Society Cafe”)

* Live Events & Meetups
  Add events, study sessions, open mics, and local gatherings to the map where users can attend or host events directly through Spotly

* AI Vibe Recommender
  Suggests new spots and experiences based on your saved posts, mood, or favourite “vibe” tags

* Time Based Vibes
  Places could change vibe dynamically depending on the time of day “study cafe by day, live music bar by night”

* Explore Mode/Street View
  A creative 3D walking experience inspired by Google street view, letting users virtually “walk” through the most recommended spots

* Mood Map Mode
  The entire map visually changes colour based on the most popular vibes in different areas a living, emotional snapshot of the city

* Community & Social Layer

  * Add friends and follow other users
  * Create and share “Vibe Trails” (e.g. Best coffee spots*, *sunday chill route)
  * Group chat or DM people you meet through local events

* AI Story Builder
  Auto generates short captions or posts based on photos and location data, helping users describe their experiences creatively

* Expand Beyond Bath
  Eventually scale Spotly to other university cities like Bristol, London, or Manchester, this way creating a connected student map network across the UK



## **How It Uses Data**

* MongoDB stores user accounts, posts, locations, and events
* Express & Node.js handle routes, authentication, and APIs
* Leaflet or Mapbox API for the interactive map
* (Future) Integrations with external APIs for events or weather
* Secure authentication to protect user data and personal experiences


## **Novel User Experience**

Unlike traditional review apps, Spotly focuses on vibe based discovery, people explore cities through moods and moments rather than star ratings.
It blends the feel of a social network with the practicality of a map

Every feature is designed to feel personal, visual, and community driven, so users feel like they’re getting local advice from real people, not just reviews


## **Target Audience**

* University students and young adults living in or new to Bath
* Locals who want to share genuine recommendations
* Visitors who prefer personal, trustworthy insights instead of corporate guides

Spotly’s friendly and visual design makes it accessible, modern, and fun, built for people who value real experiences over algorithms


## **Inspirations**

* **Google Maps** for core navigation and pins
* **Airbnb** for rich visuals, map/list sync, and smooth user flow
* **TripAdvisor** for community reviews
* **Instagram Stories** for visual storytelling
* **Nextdoor / Meetup** for local connection and events

*Note:* Airbnb doesn’t offer a public API, Spotly doesn’t use Airbnb data, only draws inspiration from its design and interaction patterns.

Spotly combines these familiar ideas in a new, youth driven, and playful way.


## **Planned Tech Stack**

| Layer              | Tools                                               |
| ------------------ | --------------------------------------------------- |
| **Frontend**       | HTML, CSS, JS (EJS templates or React)              |
| **Backend**        | Node.js + Express                                   |
| **Database**       | MongoDB + Mongoose                                  |
| **Authentication** | Passport.js or JWT                                  |
| **Map API**        | Leaflet or Mapbox                                   |
| **Hosting**        | Render, Railway, or Vercel                          |
| **(Optional)**     | Three.js for 3D visuals, OpenAI API for AI features |


## **Project Status**

**Stage:** Concept & planning (S2a submission)
**Next:** Build the initial Node/Express structure and integrate the map API (S2b)


## **Developer & Author**

👤 **Anri [@anri89](https://github.com/anri89)**
Creative Computing (Web Technologies)
Bath Spa University
