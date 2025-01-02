# Real-Time Misinformation Detection and Fact-Checking System

This provides realtime livestream fact-checking and emotional analysis for a more informed and transparent viewing experience.

## Tech Stack

- **Framework**: Next.js
- **APIs**: Groq, Hume, You.com
- **Styling**: Tailwind CSS

## Running Locally

### Getting API Keys.

The following environment variables are used in this project:

- `NEXT_PUBLIC_GROQ_API_KEY`: API key for accessing Groq services. Get one [here](https://console.groq.com/).
- `NEXT_PUBLIC_HUME_API_KEY`: API key for accessing Hume's services. Get one [here](https://dev.hume.ai/docs/introduction/api-key).
- `YOU_DOT_COM_API_KEY`: API key for accessing You.com services. Get one [here](https://api.you.com/).

Rename `.env.example` and populate the values. Warning: Remember to check the [docs](https://nextjs.org/docs/pages/building-your-application/configuring/environment-variables) about public environment variables before you deploy to production.

### Installing dependencies.

```console
bun install
```

## Additional Notes

- Trying to target the following problem: Misinformation and disinformation through livestreams is incredibly rampant.
- This idea is just a **proof-of-concept**. The integration may not be the best, but I believe there is definitely a future in which this service is commonly used and extremely impactful.
