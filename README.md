<!-- PROJECT LOGO -->
!["CA VA - CA VA"](./githubWhite.png)
<h3 align="center">Strapi</h3>

<p align="center">
    API creation made simple, secure and fast.
    The most advanced open-source Content Management Framework to build powerful API.
</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone git@github.com:happy-game/back.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

## Available Scripts

### `npm run develop`

Start a Strapi application with autoReload enabled.

Strapi modifies/creates files at runtime and needs to restart when new files are created. To achieve this, strapi
develop adds a file watcher and restarts the application when necessary.

### `npm run start`

Start a Strapi application with autoReload disabled.

This commands is there to run a Strapi application without restarts and file writes (aimed at production usage). Certain
features are disabled in the strapi start mode because they require application restarts.

### `npm run build`

Builds the administration panel and minimizing the assets




