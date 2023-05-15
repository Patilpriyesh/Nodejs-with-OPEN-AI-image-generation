# OpenAI Image Generator

This is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images. Reference is from  [Brad Traversey](https://beta.openai.com/docs/guides/images](https://github.com/bradtraversy/nodejs-openai-image)), changes th Api key from OPEN AI to RAPID API due to some issuse with billing and using the request module for the requeset

<img src="public/img/screen.png" width="500">

## Usage

Rename the `example.env` file to `.env`.

Generate an API KEY at [Rapid API](https://rapidapi.com/hub) for the OPENAI and add it to the `.env` file.

Install the dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Visit `http://localhost:5000` in your browser.

The endpoint is at `POST http://localhost:5000/openai/generateimage`.