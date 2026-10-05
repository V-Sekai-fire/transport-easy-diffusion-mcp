# transport-easy-diffusion-mcp

A Model Context Protocol server, written in Elixir, that exposes a local diffusion image server as one image-generation tool.

## What it is for

It forwards each `generate_image` call to the image server's render API and returns the finished batch. It has no authentication, so it belongs on a trusted local network. It reads its settings from the environment, and `.env.example` names them.

## Build and run

```sh
mix deps.get
mix run --no-halt
```

## Licence

The licence is not stated.
