# Heroku Buildpack for the Github CLI

This is a buildpack for the Github CLI.
The code is taken from the heroku/salesforce-cli-buildpack..

## Plugins

The Github CLI comes with the following plugins :

- gh annotations

## Usage

To use `gh`, you simply need to export the appropriate paths:

```
export PATH="$BUILD_DIR/vendor/github/cli/bin:$PATH"
```

The `$BUILD_DIR` is the path where your apps source is stored on the Heroku dyno.
