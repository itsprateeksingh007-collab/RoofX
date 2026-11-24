# RoofX

A lightweight static website built from standalone HTML, CSS, and JavaScript. There is no build step or framework dependency.

## Pages

- `/` — RoofX home
- `/listing` — home listing
- `/preferences` — roommate preferences
- `/chat` — host conversation
- `/room` — scroll-driven room transformation

The `.html` suffix also works for each page.

## Run locally

From this directory, run:

```sh
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

## Deploy to Vercel

Import this repository into Vercel and deploy it as a static site. Leave the framework preset as **Other** and keep the build command and output directory empty/default. Vercel serves `index.html` from the project root; `vercel.json` enables clean URLs such as `/listing`.
