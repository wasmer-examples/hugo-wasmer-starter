# HUGO Starter template for Wasmer Edge

This is a template project for creating a HUGO based website that can be deployed to Wasmer Edge

## Usage

### 1. Install the `wasmer` CLI

```bash
curl https://get.wasmer.io -sSfL | sh
```

### 2. Clone this repository

```bash
git clone https://github.com/wasmer-examples/hugo-wasmer-starter.git
```

### 3. Install the Hugo CLI

```bash
brew install hugo
```

### 4. Add your Hugo site

Add your data to the `content` folder.

### 5. Run the Hugo site

```bash
hugo server
```

You will get the output from the Hugo site.

### 6. Deploy the Hugo site

```bash
wasmer deploy
```

> You will need to change the namespace in `wasmer.toml` to your own namespace and app name in `app.yaml` to your own app name.
