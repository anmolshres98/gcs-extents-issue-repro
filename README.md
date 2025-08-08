
# gcs-extents-issue-repro

This repo is created to reproduce a bug with the itwin repo.

## Installation & Startup Instructions

This repository contains two apps: `desktop-viewer` and `web-viewer`.

### Prerequisites
- [Node.js](https://nodejs.org/) 
- [pnpm](https://pnpm.io/) package manager

### Install dependencies
Run the following commands in each app directory:

```bash
cd desktop-viewer
pnpm install

cd ../web-viewer
pnpm install
```

### Start the apps
To start the desktop viewer:

```bash
cd desktop-viewer
pnpm start
```

To start the web viewer:

```bash
cd web-viewer
pnpm start
```

Both apps will start their respective development servers. Follow any additional instructions in their individual README files if needed.

---

## Checking CRS Extents

After starting the apps, open the browser or application console log to observe the difference in horizontal CRS extents values. 
