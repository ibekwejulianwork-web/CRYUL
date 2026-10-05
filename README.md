# CRYUL

CRYUL is one project in three folders. The site shows public prices for Bitcoin, Ethereum, and Solana in euros, and the texts written in Strapi. It does not buy or sell, and it does not use real money.

This repository is the copy kept on GitHub. Day-to-day work stays in the original folders on the computer, because this copy does not include `node_modules`, `.env` files, or the Strapi database.

## Folders

| Folder | What it is |
| --- | --- |
| `cryul-web` | The website. Open [its README](cryul-web/README.md) for pages, prices, and how to start it. |
| `my-strapi-project` | The content desk for the About page and the articles. Admin, when it is running: [http://localhost:1337/admin](http://localhost:1337/admin). |
| `portfolio-project` | Reserved for the portfolio. It will become a page of the site. It is empty for now. |

## Run it on your computer

Use the original folders, not this copy, if those folders still have `node_modules` and the `.env` files.

Site, in `cryul-web`:

```bash
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000).

Strapi, in `my-strapi-project`:

```bash
npm install
npm run develop
```

Then open [http://localhost:1337/admin](http://localhost:1337/admin).

`localhost` means this computer. The site is not online.

## What is not here yet

- No public domain.
- No buy or sell orders.
- No portfolio page inside the site. The `portfolio-project` folder is the place held for it.
