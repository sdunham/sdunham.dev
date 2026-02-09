# sdunham.dev

Personal website for Scott Dunham - Web Developer at SiteCrafting in Tacoma, WA.

## Tech Stack

- **Framework**: SvelteKit
- **Language**: TypeScript
- **Hosting**: Cloudflare Pages
- **Styling**: Vanilla CSS (minimal and clean)

## Development

Install dependencies:
```bash
npm install
```

Start the development server:
```bash
npm run dev
```

Open the app in a browser:
```bash
npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

## Deployment to Cloudflare Pages

This project is configured to deploy to Cloudflare Pages using the `@sveltejs/adapter-cloudflare` adapter.

### Cloudflare Pages Configuration

- **Build command**: `npm run build`
- **Build output directory**: `.svelte-kit/cloudflare`
- **Framework preset**: SvelteKit

### Deploy via Cloudflare Dashboard

1. Log in to [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Go to "Workers & Pages" → "Create application" → "Pages"
3. Connect your Git repository (GitHub, GitLab, etc.)
4. Configure build settings:
   - Build command: `npm run build`
   - Build output directory: `.svelte-kit/cloudflare`
   - Framework preset: SvelteKit
5. Deploy

Cloudflare Pages will automatically rebuild and deploy on every push to your repository.

### Deploy via Wrangler CLI (optional)

You can also deploy using the Wrangler CLI:

```bash
npx wrangler pages deploy .svelte-kit/cloudflare
```

## Contact

Scott Dunham - [dunham.scott@gmail.com](mailto:dunham.scott@gmail.com)

SiteCrafting Profile: [https://www.sitecrafting.com/team/scott-dunham/](https://www.sitecrafting.com/team/scott-dunham/)
