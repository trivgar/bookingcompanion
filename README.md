# bookingcompanion.app

Static landing page for [Booking Companion](https://bookingcompanion.app),
a multi-tenant booking platform for independent salons. The companion
operator app lives in [`trivgar/roberta-salon`](https://github.com/trivgar/roberta-salon).

## Stack

Single `index.html` + Tailwind via CDN. No build step.

## Deploy

```sh
npx wrangler pages deploy . --project-name bookingcompanion --branch main
```

The custom domain `bookingcompanion.app` is attached in the Cloudflare
Pages dashboard (Pages → bookingcompanion → Custom domains).
