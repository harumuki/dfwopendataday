# DFW Open Data Day Site

URL: http://www.dfwopendataday.com

DFW Open Data Day is a civic technology hackathon focused on spurring civic engagement, utilizing open data, improving open government policies, and bolstering smart city innovations.


## How to install/run locally
This is a static site hosted on Github Pages using the Jekyll static site generator.

- Download/clone the repo and navigate to the directory.
- If you don't have Jekyll installed, install it: `gem install jekyll`
- Navigate to the repo directory and install dependencies:
```bash
   bundle install
   npm install
```
- Run Jekyll: `jekyll serve` or `jekyll s`
   - If this doesn't work, you can try `bundle exec jekyll serve`

## Conflicts
Sometimes when running into gem version conflicts, these can be remedied by cleaning up the gems and re-installing them.
```bash
bundle clean --force
bundle install
```

## Using Gulp
When developing, use the built in npm scripts to start the Jekyll server, compile/minify scripts and styles, and start a Browsersync session at the same time.
```bash
npm run start
```
This should launch a new localhost tab running at `localhost:3000`.
