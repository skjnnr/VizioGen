# VizioGen

VizioGen is a GitHub-ready AI image generator with dedicated Thumbnail and Picture modes. It uses a Vercel serverless API route so the OpenAI API key stays private on the server.

## Features
- Thumbnail and Picture generation modes
- Landscape, square, and portrait size choices
- Low, standard, and high quality choices
- Prompt examples and character counter
- Responsive desktop/mobile design
- Loading and error states
- PNG download
- Server-side OpenAI API integration

## Deploy with GitHub + Vercel
1. Extract this ZIP.
2. Create a GitHub repository and upload the contents of the `viziogen` folder (not the outer ZIP itself).
3. In Vercel, import that GitHub repository.
4. In the Vercel project, open Settings > Environment Variables.
5. Add `OPENAI_API_KEY` and paste your OpenAI API key as its value.
6. Redeploy the project after adding the environment variable.
7. Open the Vercel URL and generate an image.

Never put your API key in `public/app.js`, `index.html`, GitHub, or any other public file.

## Run locally
Install Node.js, then run:

    npm install

Create `.env.local` containing:

    OPENAI_API_KEY=your_key_here

Then run:

    npx vercel dev

Open the local URL printed by Vercel.

## Important before selling access
This build is a working single-user/public generator once an API key with billing is configured. Before opening it to lots of users, add authentication, per-user generation limits/credits, abuse protection/rate limiting, and payment handling so strangers cannot freely spend your API balance.
