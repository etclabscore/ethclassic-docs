# Ethereum Classic Technical Documentation

<!-- project shields -->
  <span>
    <a target="_blank" href="https://discord.gg/S9AT3X2"><img alt="Chat on Discord" src="https://img.shields.io/badge/chat-on%20discord-7289da.svg" /></a>
  </span>

<!-- project logo w/ quick links -->
<p align="center">
  <img src="website/static/img/readme.png" />
</p>
<center>
  <h3 align="center">Ethereum Classic Docs</h3>

  <p align="center">
    A website for classic EthereumStack developers.
    <br />
    <a href="https://docs.ethereumclassic.org/">View Demo</a>
    ·
    <a href="https://github.com/etclabscore/ethclassic-docs/issues/new?assignees=&labels=&template=bug_report.md&title=">Report Bug</a>
    ·
    <a href="https://github.com/etclabscore/ethclassic-docs/issues/new?assignees=&labels=&template=feature_request.md&title=">Request Feature</a>
  </p>
</center>

<!-- table of contents -->
## Table of Contents
  - [About The Project](#about-the-project)
  - [Getting Started](#getting-started)
      - [Prerequisites](#prerequisites)
      - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Resources](#resources)

<!-- about the project -->
## About The Project

This project is an open-source technical documentation resource for classic EthereumStack developers. This solution is live at https://docs.ethereumclassic.org. Everyone is welcomed to contribute to this project simply see [CONTRIBUTING](#contributing) for contributing guidance.

<!-- getting started with the project -->
## Getting Started

This project uses the _Docusaurus_ website generator. The `src` branch contains the source files, and `gh-pages` is the deployed build.

### Prerequisites

- Docusaurus, read the docs at https://docusaurus.io/docs/en/
- Node >= 8.x and/ or Yarn >= 1.5.

### Installation

Install docusaurus on your machine. [Need help?](https://docusaurus.io/docs/en/installation#installing-docusaurus)

### Run local build

To run the website locally run `npm start` in the `website/` directory. Changes will be seen in realtime at http://localhost:3000/. If changes are not shown just `npm start` again.

<!-- example usage, screen shots, demos -->
## Usage

Clone _your_ fork of this repository. Ensure you're working in the `src` branch. The `src` contains two key directories, `website/` and `docs/`.

- `docs/` contains Markdown documentation files.
- `website/` site configuration, static assets, and page components.
- `website/blog` contains blog posts.

### Contribute a blog post.

Fork the repo, create your blog post as a Markdowwn file in `website/blog`, and submit a Pull Request. Use existing posts as a reference, however your post should meet the following minimum requirements.
- At the heading of your Markdown file. Please input article title, author name, and author url (twitter link).
    ```md
    ---
    title: INPUT ARTICLE TITLE
    author: INPUT AUTHOR NAME
    authorURL: INPUT AUTHOR URL (TWITTER LINK)
    ---
    ```
- Name the markdown file like so `YEAR-MM-DD-TITLE.md`, `2020-02-24-etc-to-the-moon.md`.

<!-- template just leave alone  -->
## Roadmap

See the [open issues](https://github.com/etclabscore/ethclassic-docs/issues) for a list of proposed features (and known issues).

<!-- template just leave alone  -->
## Contributing

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.

## License

Apache License 2.0

<!-- references and additional resources  -->
## Resources 
- https://docs.ethereumclassic.org/
- https://docusaurus.io/docs/en/
