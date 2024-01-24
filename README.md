This is a [Hugo](https://gohugo.io/) project bootstrapped with `hugo new site project-name`.

## Usage

You can run the Hugo site with:

```bash
hugo server
```

You will start a high-performance server that will watch your files.

### Deploy Wasmer Edge

The easiest way to deploy your Hugo static site is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: http://wasmer-edge-hugo-sample.wasmer.app/

First, you'll need to run `hugo` to build the assets, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```

> [!NOTE]
> You will need to have Wasmer installed (check out [the docs to install the Wasmer CLI](https://docs.wasmer.io/install)!). 
> You will also need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
