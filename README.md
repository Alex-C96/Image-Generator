﻿# Image-Generator

This is a simple image generator built with Node.js and Express that uses OpenAI's Dall-E models to generate images.

![Front Page](/public/img/cat_playing_trumpet_while_surfing.PNG)

# Replicate
- - - -
Create a `.env` file.

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

Install the dependencies

```
npm install
```
Run server
```
npm start
```
visit `http://localhost:5000` in your browser.
The endpoint is at `POST http://localhost:5000/openai/generateimage`.
