# RLEM Workshop Website

RLEM brings together researchers and industry practitioners for the advancement of (deep) reinforcement learning (RL) in the built environment as it is applied for managing energy in civil infrastructure systems (energy, water, transportation).

This repository holds the source files that are used to build and maintain the [rlem-workshop.net](http://www.rlem-workshop.net/) website. The website theme is taken from [jekyll-theme-conference](https://github.com/DigitaleGesellschaft/jekyll-theme-conference).

# Local Build (MacOS)
Follow these [instructions](https://jekyllrb.com/docs/installation/macos/) to install Ruby and Jekyll on MacOS.

Bundle the website dependencies:
```console
bundle
```

Finally, build and run the site locally:
```console
bundle exec jekyll serve --trace --watch
```

A `_site` directory will be created that holds the website content and ideally, the content should not be manually edited nor pushed to the remote branch of this repository.

# GitHub Actions Build
The website is located at [rlem-workshop.net](http://www.rlem-workshop.net/) and uses GitHub Actions for continuous deployment.

To make changes to the website, commit changes to the [main branch](https://github.com/intelligent-environments-lab/rlem-workshop.net/tree/main) and push to the remote branch. The [build.yml](https://github.com/intelligent-environments-lab/rlem-workshop.net/blob/main/.github/workflows/build.yml) workflow will run the jekyll build remotely and deploy the site content to the [gh-pages branch](https://github.com/intelligent-environments-lab/rlem-workshop.net/tree/gh-pages). Another Github Action workflow, handled by GitHub will re-build the website using the content in `gh-pages`.

__Do not directly edit `gh-pages` branch!__

