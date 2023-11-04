# Profile App

Profile is an experimental link-in-bio tool, where the data lives in the URL. 

![image](https://github.com/Umangmodii/Profile-App/assets/122307664/ab6d1056-3cc9-4e43-af8a-1151594a0296)



Here's a demo page
https://identity-profile.vercel.app/1?data=eyJuIjoiVW1hbmcgTW9kaSIsImQiOiJJIGFtIFN0dWRlbnQgT2YgTS5TQyAoQy5BICYgSS5UKSIsImkiOiJodHRwczovL2F2YXRhcnMuZ2l0aHVidXNlcmNvbnRlbnQuY29tL3UvMTIyMzA3NjY0P3M9NDAwJnU9ZDAwNmEzZjU4YzlmYjEwMzc3ZTNiNGU1NzQ0YWMwNTNlZTViYzg4OSZ2PTQiLCJmIjoiaHR0cHM6Ly93d3cuZmFjZWJvb2suY29tL0pvdGZvcm0vIiwidCI6IiIsImlnIjoiaHR0cHM6Ly93d3cuaW5zdGFncmFtLmNvbS9jb2Rld2l0aHVtYW5nLyIsImdoIjoiaHR0cHM6Ly9naXRodWIuY29tL1VtYW5nbW9kaWkiLCJ0ZyI6IiIsImwiOiJodHRwczovL3d3dy5saW5rZWRpbi5jb20vY29tcGFueS9qb3Rmb3JtIiwiZSI6InRlY2h3ZWJ1bWFuZ0BnbWFpbC5jb20iLCJ3IjoiOTMxMzc0NDIzOSIsInkiOiIiLCJscyI6W3siaSI6IiIsImwiOiJCdXNpbmVzcyBXZWJzaXRlIiwidSI6Imh0dHBzOi8vdW1hbmdtb2RpLmJ1c2luZXNzLnNpdGUvIn0seyJpIjoiIiwibCI6IlBlcnNvbmFsIFdlYnNpdGUiLCJ1IjoiaHR0cHM6Ly90ZWNodW1hbmcubmV0bGlmeS5hcHAvIn0seyJpIjoiIiwibCI6IlBvcnRmb2xpbyBXZWJzaXRlIiwidSI6Imh0dHBzOi8vdW1hbmdtb2RpLndlYnNpdGUzLm1lLyJ9LHsiaSI6IiIsImwiOiIiLCJ1IjoiIn1dfQ==

The data is converted to a base 64 string which we onelink uses as a query parameter. I have tried to reduce the json keys to be as small as possible

Roadmap.
1. Templates - make different templates, the `/1` after the host is basically a template here.
2. Refactor code - a lot of repeated boilerplate code is added here - refactor it properly.

## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.
