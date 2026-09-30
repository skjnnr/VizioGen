# VizioGen
AI thumbnail + picture generator starter website.

## Deploy with GitHub + Vercel
1. Upload this project's files to a GitHub repository.
2. Import the repository into Vercel.
3. In the Vercel project, add an environment variable named `OPENAI_API_KEY` containing your OpenAI API key.
4. Deploy.

Do not put the API key in `public/app.js` or commit a `.env` file to GitHub.

## Features
- Thumbnail and Picture modes
- Size selector
- Quality selector
- AI image generation
- PNG download
- Responsive dark UI

## Notes
Image generation uses the OpenAI API and therefore has API usage costs. Add authentication, rate limits/credits, database storage, and payments before offering this as a public paid service.
