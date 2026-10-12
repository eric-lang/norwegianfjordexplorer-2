# Norwegian Fjord Explorer — V2

Astro website for Norwegian Fjord Explorer, using V2's design and V1's cruise content.

Live site: https://norwegianfjordexplorer-2.vercel.app/

## Local development

Requires Node.js 24 and pnpm 11.25.0.

```sh
pnpm install
pnpm dev
pnpm check
pnpm build
```

The development server runs at http://127.0.0.1:4322/.

## Deployment

Vercel project: `jeo-studio/norwegianfjordexplorer-2`.

```sh
pnpm dlx vercel deploy --prod
```

Original design archives, local inspection data, caches and the uncompressed video remain outside version control. Runtime fonts and optimized images/video are included in `public/`; attribution files accompany the assets.
