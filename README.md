# Sustainability Awareness Website

A six-page website about energy, water and land sustainability, developed as a four-person university group project using Node.js, Express and JavaScript.

## Features

- Home, Energy, Water, Land, Team and Get Involved pages.
- Navigation and page content populated from a shared JSON file.
- Video sections, FAQs, responsive styling and interactive team-member cards.
- An Express server which serves static files and accepts a `POST /form` request.

The form currently logs the request and returns JSON. It does **not** save submissions or send email.

## Run locally

Requires Node.js and npm.

```bash
cd node-express/app
npm install
npm run dev
```

Then open `http://localhost:3000`. Use `npm start` to run without Nodemon. Content and front-end scripts live under `node-express/app/public/`, with shared content in `data.json`.

## My contribution

My contributions were the homepage video and overlay, Land page, Team page and GitHub hosting. The initial structure and other sections were shared among the four-person team, whose contributions are described on the site's Team page.

This is student coursework and is not an official United Nations website. Some included media may be subject to third-party licences.
