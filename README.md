# Workshop Catalog Site

This is the project you will build on in the three-session web workshop. It is a working website with a public catalog, contact forms, memberships paid by GCash, donations, and Staff and Admin dashboards.

As this is an introductory workshop, there is no need to write manual code from scratch, hence this will be a build-along workshop. You will make your own copy, deploy it online, change a few files and connect to your own database.



## The files you will change

| File | What it controls | When |
|------|------------------|------|
| `content/site.ts` | Your site name, headline, and intro text | Session 1 |
| `content/listings.ts` | The services in your catalog | Session 1 |
| `public/images/` | The pictures on your catalog cards | Session 1 |
| `content/payment.ts` | Your GCash payment details | Session 2 |
| `public/images/gcash-qr.png` | Your GCash QR code picture | Session 2 |

## Run it on your computer

```bash
npm install
npm run dev
```

Then open [http://localhost:3000](http://localhost:3000) in your browser. In doing so you have launched your own local server of the website!

## What is in this project

| Folder | What is inside |
|--------|----------------|
| `content/` | The text and settings you customize |
| `public/images/` | Pictures used on the site |
| `app/` | The pages and the server code |
| `lib/` | Shared helpers the pages use |
| `db/` | The SQL files you run in Supabase in Sessions 2 and 3 |



