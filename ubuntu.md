# Ubuntu Setup Guide

## Install Node.js
- Update package metadata: `sudo apt update`
- Install prerequisites for repository management: `sudo apt install -y ca-certificates curl gnupg`
- Add the NodeSource repository for the current LTS release:
  - `curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -`
- Install Node.js and npm: `sudo apt install -y nodejs`
- Verify the versions: `node -v` and `npm -v`

## Run This Project
- Open a terminal and move into the project directory, for example:
  - `cd ~/Personal-Website-Template-main`
- Install dependencies: `npm install`
- Start the development server: `npm start`
- Visit `http://localhost:3000` in a browser to view the site; edits under `src/` hot-reload.
