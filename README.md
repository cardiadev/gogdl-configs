
# Gogdl App - Configs

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

**GoGDL-Configs** is the main configuration repository for the GoGDL project. It manages and organizes the structure of the project, incorporating submodules for different components. Each component lives in its own repository (poly-repo), and this repo only keeps the folder layout and submodule metadata.

- **Angular Web App**: `modules/apps/gogdl-angular` (existing front-end)
- **Next.js Web App**: `modules/apps/gogdl-web` (placeholder for the upcoming Next.js repo)
- **Expo Mobile App**: `modules/apps/gogdl-mobile` (placeholder for the upcoming Expo repo)
- **NestJS API**: `modules/services/gogdl-api` (existing backend)

| Repo | Location | Remote |
| --- | --- | --- |
| gogdl-angular | `modules/apps/gogdl-angular` | `git@github.com:cardiadev/gogdl-angular.git` |
| gogdl-web | `modules/apps/gogdl-web` | `git@github.com:cardiadev/gogdl-web.git` |
| gogdl-mobile | `modules/apps/gogdl-mobile` | `git@github.com:cardiadev/gogdl-mobile.git` |
| gogdl-api | `modules/services/gogdl-api` | `git@github.com:cardiadev/gogdl-api.git` |

This repository serves as a central hub for coordinating development, ensuring consistency across the project's components.

## Branching Model

- `main`: stable configuration snapshots.
- `develop`: active coordination branch. All structural work (like folder/layout changes) should originate here before being merged into `main`.





## Setup & Installation

### Initial Clone

Clone the main repository with all submodules:

```bash
git clone --recurse-submodules git@github.com:cardiadev/gogdl-configs.git
cd gogdl-configs
```

### Alternative: Clone without submodules first

If you've already cloned the repository without submodules:

```bash
git clone git@github.com:cardiadev/gogdl-configs.git
cd gogdl-configs
git submodule update --init --recursive
```

### Install Dependencies

Each submodule requires its own dependencies to be installed:

#### Angular App
```bash
cd modules/apps/gogdl-angular
npm install
```

#### Next.js Web App
```bash
cd modules/apps/gogdl-web
npm install
```

#### Expo Mobile App
```bash
cd modules/apps/gogdl-mobile
npm install
```

#### NestJS API
```bash
cd modules/services/gogdl-api
npm install
```

### Running the Applications

Each application can be run independently from its respective directory. Check each submodule's README for specific run commands and environment setup instructions.



## Tech Stack

**Angular App:** Angular 19, TypeScript, SCSS, Mapbox GL  
**Next.js App:** Next.js, React, TypeScript  
**Mobile App:** Expo, React Native, TypeScript  
**Backend API:** NestJS, TypeScript, MongoDB


## Authors

- Carlos Diaz [@cardiadev](https://github.com/cardiadev)

