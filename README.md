# A same page

This is my website Jekyll template. The website can be written in pure HTML and css; however, I ported it to Jekyll for easier maintenance.
All layouts are in pure HTML with simple CSS.

[Demo (links might not work properly)](https://khanhdang.github.io/sample-profile-page/).

Some features (or maybe not really features at all):
- No menu just for simplicity
- Mobile friendly with adaption
- Lightweight 


## How to use

1. Visit the repository at [https://github.com/khanhdang/sample-profile-page](https://github.com/khanhdang/sample-profile-page)
2. Fork it to a new repository (make it public)
3. Edit the information in `_config.yml` and the page at `index.md`.
4. In the repository, go to "Settings", then "Pages". Select the branch (default to main) to build GitHub page. Wait for 3-4 mins and refresh. The page URL will appear in the "Pages" section.
5. Wait for github page to be built. Example is here: [https://khanhdang.github.io/sample-profile-page/](https://khanhdang.github.io/sample-profile-page/)

## Run locally

Jekyll and bundle need to be installed.
```
make run # to run the local website at 127.0.0.1:4000
make build # to build the _site folder
make clean # to clean up the repo
```