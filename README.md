# AstroMind
AstroMind – a chatbot that combines NASA, ISRO and ESA data to show space images, launches and missions on one single chatbot. 
AstroMind chatbot – NASA, ISRO & ESA Data (Team Astrominds)

SpaceBot is a **React-based web application** that integrates data from NASA, ISRO, and ESA into a single interactive platform.  
It allows users to explore real-time space data, missions, images, and launch information without leaving the website.

---

## Features

- NASA Astronomy Picture of the Day (APOD) 
  Fetches and displays NASA’s daily image with its title and explanation.
  
- ISRO Launchers & Spacecraft Data
  Shows information about ISRO launchers (rockets) from an open ISRO API.

- ESA Missions (Prototype)
  Demonstrates integration of ESA mission data (can be extended to satellites, images, or research projects).

- Single Interface  
  Combines all three space agencies’ data on one website.

- Firebase Hosting  
  Hosted online for easy access during competitions and demos.

---

## Tech Stack

- Frontend: React.js (JavaScript)
- APIs Used:
  - [NASA Open API](https://api.nasa.gov/)
  - [ISRO Open API](https://isro.vercel.app/)
  - [ESA Community Data/API](https://api.sesam.space/missions) (Demo endpoint)
- Hosting: Firebase Hosting
- Version Control: Git & GitHub

---

## How It Works

1. The application fetches data from NASA, ISRO, and ESA APIs using `fetch()` in React.
2. JSON responses are rendered directly on the webpage (images, text, lists).
3. Users can explore multiple agencies’ data without leaving the site.
4. Future versions will allow search, filters, and chatbot Q&A.

   
## Future Improvements
- Self-hosted star map (using D3 Celestial / Three.js)
- Personalised sky views based on the user’s location.
- Chatbot with multilingual support.
- Integrate satellite tracking & upcoming launches timeline.
- Mobile-friendly UI & dark mode.
