## Planet Vune

Inspired by the legacy of Vine, we decided to create a blogging/social platform for uploading and sharing 7-second videos in a 
geographical context. Vune enables people to upload videos at a specific location, and to share these videos with their 
subscriber/follower base. We implemented real-time Firebase sync across our entire platform, so videos are visible to others as 
soon as they are uploaded, without having to refresh the page. This project was developed and submitted for Hack the North 2017.

## How We Built It

We ended up building two-frontends; our main frontend is deployed via Firebase hosting and is hosted at 
https://hot-spot-40dff.firebaseapp.com/index.html. However, our second frontend has a more polished UI and is powered by Vue.js, Vuex and 
Vue-Router. It has been deployed via Netlify and can be viewed at https://www.getvune.com/. Before deciding on transitioning to Firebase, we initially wrote a few REST API endpoints in Node.js to handle the uploading and retrieval of videos. This backend code can be found at: https://github.com/Cvarier/planet-vune-backend.

<p align="center"><img src ="https://user-images.githubusercontent.com/16710726/30573605-dae35cec-9cc2-11e7-8382-f95f3be4943c.png"/></p>
A schematic of our service-oriented architecture.

## Milestones

Building a Vue.js / Vuex / Vue-router, components-based backend with almost no prior Vue experience, using Firebase to integrate
user authentication and management as well as allow the simulataneous upload and distribution of videos to users.

## What We Learned

How to use Vue to build a modern front-end, use Netlify to deploy with continuous deployment from a GitHub repository, 
use Google App Engine to deploy and package our API which connected to Firebase, and use Firebase to host video files, 
store the geographical data associated with each video, and stream the videos back to users on our platform.

## What's next for Vune

Flesh out the API and complete:

- Advertising system for funds
- Subscriber / following system
- Recommendation engine
- Mobile App

