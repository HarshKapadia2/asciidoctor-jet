# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0) and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.1] - 2021-12-25

### Fixed

-   The GitHub Actions workflow now downloads the missing `rsync` package [required by the Deploy Action](https://github.com/marketplace/actions/deploy-to-github-pages#using-a-container-).

## [0.1.0] - 2021-12-25

### Added

-   `index.adoc` and other `.adoc` files for the website content.
-   A buildscript to build the Asciidoctor site.
-   A service worker, webmanifest and icons to convert the site to a PWA.
-   A 'back to top' button.
-   A theme switcher.
-   A `robots.txt` file.
-   Images for the demo site.
-   A GitHub Actions workflow to build the site (for PRs) and to build and deploy the site to GitHub Pages (on merges and pushes).
