This is a [Hugo](https://gohugo.io/) project bootstrapped with `hugo new site project-name`.

## Usage

You can run the Hugo site with:

```bash
hugo server
```

This will start a high-performance server that will watch your files.

You can run the Hugo website using Wasmer (check out the [install guide](https://docs.wasmer.io/install)):

```bash
wasmer run wasmer-examples/hugo-wasmer-starter --net -- --port=1313
```

> [!TIP]
> You can also run `wasmer run . --net -- --port=1313` in the root of this repo, after running `hugo`

Open [http://localhost:1313](http://localhost:1313) with your browser to see the result.


## Deploy Wasmer Edge

The easiest way to deploy your Hugo static site is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://wasmer-edge-hugo-sample.wasmer.app/

First, you'll need to run `hugo` to build the assets, and then, to deploy to Wasmer Edge:

```bash
wasmer deploy
```

> [!NOTE]
> You will need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
