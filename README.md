# Hugo Static Site + Wasmer

This example shows how to build a **Hugo** site and deploy the generated HTML to **Wasmer Edge**.

## Demo

https://wasmer-edge-hugo-sample.wasmer.app/

## How it Works

* `hugo.toml` defines the site title, base URL, and theme (`ananke`).
* Content lives under `content/`; run `hugo new` to add more pages or posts.
* The bundled `themes/ananke` theme provides layouts and styling.
* `hugo` builds everything into the `public/` directory—exactly what Wasmer Edge serves.

## Running Locally

```bash
hugo server
```

The development server watches your files and serves the site at `http://127.0.0.1:1313/` with live reload.

## Deploying to Wasmer (Overview)

1. Generate the static site: `hugo` (outputs to `public/`).
2. Configure Wasmer Edge to publish the `public/` directory.
3. Deploy and open `https://<your-subdomain>.wasmer.app/` to view the site.
