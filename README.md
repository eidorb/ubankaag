# ubank@ag

[ubank](https://www.ubank.com.au) at a glance


## Getting started

It's easy to start developing locally:

1. Install [uv](https://docs.astral.sh/uv/):

  ```bash
  curl -LsSf https://astral.sh/uv/install.sh | sh
  ```
2. Serve the Textual demo app from the development environment (installing/updating Python and package dependencies as required):

  ```bash
  uv run textual serve "python -m textual"
  ```
3. 🙇

Alternatively, you can activate a shell in the environment:

```bash
uv sync
source .venv/bin/activate
```

And run commands as usual:

```bash
$ which textual
/Users/eidorb/projects/ubankaag/.venv/bin/textual

$ uv run textual --help
Usage: textual [OPTIONS] COMMAND [ARGS]...

Options:
  --version  Show the version and exit.
  --help     Show this message and exit.

Commands:
  borders   Explore the border styles available in Textual.
  colors    Explore the design system.
  console   Run the Textual Devtools console.
  diagnose  Print information about the Textual environment.
  easing    Explore the animation easing functions available in Textual.
  keys      Show key events.
  run       Run a Textual app.
  serve     Run a local web server to serve the application.
```

Deactivate when you're done:

```bash
$ deactivate
```
