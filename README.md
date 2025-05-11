# wrangler-cloudflare-playwright-screenshot

Wrangler app that takes a web page screenshot using Browser Rendering with Playwright.

### Related Apps

- [cdktf-cloudflare-playwright-screenshot](https://github.com/garysassano/cdktf-cloudflare-playwright-screenshot) - Built with CDKTF instead of Wrangler.

## Prerequisites

- **_Cloudflare:_**
  - Must have set the `CLOUDFLARE_API_TOKEN` variable in your local environment.
- **_pnpm:_**
  - Must be [installed](https://pnpm.io/installation) in your system.
- **_Wrangler:_**
  - Must be [installed](https://developers.cloudflare.com/workers/wrangler/install-and-update/) in your system.

## Deployment

```sh
npx wrangler deploy
```

## Cleanup

```sh
npx wrangler delete
```

## Architecture Diagram

![Architecture Diagram](./src/assets/arch-diagram.svg)
