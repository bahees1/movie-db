## Movie Watchlist App

A responsive Single Page Application (SPA) built with React that lets users browse popular movies and curate a personal watchlist. The homepage showcases a list of trending or featured films, and users can easily add or remove their favorites to/from a local watchlist — no account required. Data persists across sessions via localStorage, ensuring your picks are saved even after refresh. With a clean UI and lightweight footprint, it's a fun and practical tool for film lovers who want to keep track of what to watch next.

## Project Screen Shot(s)

Demo Site Link: https://bahees1.github.io/movie-db/

Main Dashboard:
![image](https://github.com/user-attachments/assets/f09c437e-3a1f-4837-9d6c-b45e8c668b80)



Favorite Movies Page:
![image](https://github.com/user-attachments/assets/a7a5a306-a6a6-4d67-b770-fbab237efe03)





## Installation and Setup Instructions

Clone down this repository. You will need `node` and `npm` installed globally on your machine.  

*Cd into the repo*

Installation:

`npm install`  

To Start Server:

`npm run dev`  

To Visit App:

`http://localhost:5173/`  

## Reflection

This was a solo project I built to practice my frontend skills and deepen my understanding of React, while creating something useful for everyday movie watchers. My goal was to build a polished SPA that mimics a real-world movie watchlist product — something simple, clean, and user-friendly.

The core features are:

Browsing a list of movies

Adding/removing movies to/from a personal watchlist

Persistent localStorage saving (no backend required)

Component-based architecture with reusable logic

Although the app may look simple, it helped me work through several practical React challenges. I focused on clean state management, avoiding prop drilling, and ensuring smooth user experience across interactions. I also had to consider how to manage localStorage updates efficiently, how to conditionally render UI based on user actions, and how to keep the app responsive on smaller devices.

One learning point was thinking in components — making sure the MovieCard and Watchlist components were decoupled, reusable, and visually consistent. Another was handling persistence: syncing state with localStorage without causing double renders or stale values required attention to React’s lifecycle and useEffect hooks.

Overall, this project was a great opportunity to work on something fun and visual while strengthening key frontend fundamentals. In the future, I’d love to expand it with features like:

User login with Firebase for cross-device syncing

Movie recommendations using a machine learning model
