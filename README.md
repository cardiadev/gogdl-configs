
# Gogdl App - Configs

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

**GoGDL-Configs** is the main configuration repository for the GoGDL project. It manages and organizes the structure of the project, incorporating submodules for different components. Each component lives in its own repository (poly-repo), and this repo only keeps the folder layout and submodule metadata.

- **Angular Web App**: `modules/apps/gogdl-angular` (existing front-end)
- **Next.js Web App**: `modules/apps/gogdl-web` (placeholder for the upcoming Next.js repo)
- **Expo Mobile App**: `modules/apps/gogdl-mobile` (placeholder for the upcoming Expo repo)
- **NestJS API**: `modules/services/gogdl-api` (existing backend)

This repository serves as a central hub for coordinating development, ensuring consistency across the project's components.

## Branching Model

- `main`: stable configuration snapshots.
- `develop`: active coordination branch. All structural work (like folder/layout changes) should originate here before being merged into `main`.





## Run Locally

Clone the project

```bash
  git clone git@github.com:cardiadev/gogdl-configs.git
  cd gogdl-configs
  git submodule update --init --recursive

```



## Tech Stack

**Client:** Angular, SCSS

**Server:** Node, NestJS, MongoDB


## Authors

- Carlos Diaz [@cardiadev](https://github.com/cardiadev)

