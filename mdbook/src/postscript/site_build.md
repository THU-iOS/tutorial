# Build This Site

- [Build This Site](#build-this-site)
  - [Intro](#intro)
  - [Repository](#repository)
  - [Docs](#docs)
  - [How to Contribute](#how-to-contribute)
- [Other](#other)
  - [Change image size](#change-image-size)

## Intro
This site is generated by [mdbook](https://github.com/rust-lang/mdBook) and is issued by GitHub pages using GitHub workflow.

[mdbook](https://github.com/rust-lang/mdBook) render markdown files to html. Use `brew install mdbook` to install it on your Mac. `GitHub pages` develops this site to GitHub server.

## Repository
You can go to GitHub repo by clicking the GitHub icon in the top right corner.

## Docs
[mdbook docs](https://rust-lang.github.io/mdBook/index.html)

[mdbook docs | SUMMARY.md](https://rust-lang.github.io/mdBook/format/summary.html)

[mdbook docs | book.toml](https://rust-lang.github.io/mdBook/format/config.html)

## How to Contribute
First, clone the repo on your Mac.

Then, add your markdown files in `mdbook/src/article`. Also add your file path and title in `mdbook/src/SUMMARY`.

You should pay attention to images which are suggested to put in `mdbook/src/media` and use relative paths, or use urls instead, to avoid image disappearing.

Next, fork that repo and push your edition to your GitHub. Then make a pull request and wait until admin merge your edition.

# Other
## Change image size
```html
<img src="" style="zoom:40%"/>
```