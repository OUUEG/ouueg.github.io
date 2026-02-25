### OUUEG website
## Source code:
https://github.com/OUUEG/ouueg.github.io

## Install bundle for the first time
```bash
sudo apt install ruby ruby-dev
bundle config set --local path /home/kpal/.local/share/bundle
bundle install

cd /home/kpal/lichnoe/ouueg/ouueg.github.io
npm init -y
npm install postcss postcss-cli
```

## To update the bundle:
```bash
bundle update
```

## To update individual dependencies versions (e.g. in response for Dependabot alert)
```bash
npm update <packagename>
# or
npm update
```

## Hosted as
https://ouueg.github.io, redirection: https://ouueg.com

## To serve locally
```bash
bundle exec jekyll serve --incremental --watch --port 4545
```

## Define styles in
```
assets/css/styles.scss
```
