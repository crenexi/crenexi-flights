# Crenexi Flights

![][urlCrenexiFav]

**[fly.crenexi.com][urlFlyProd]** | [stage-fly.crenexi.com][urlFlyStage]

Landing (pun intended) for Crenexi Flights.

# Setup

## Dependencies

- NodeJS/NPM
- Font Awesome Pro

## Installation

1. **Configure**: `npm run configure`
2. **Install**: `npm run install`
3. **Start**: `npm start`

# Tooling

## Lint

- **Lint**: `npm run lint`
- **Lint & fix**: `npm run lint:fix`

## Build

- **Build plainly**: `npm run build`
- **Build development**: `npm run build:dev`
- **Build production**: `npm run build:prod`

## Maintain

- **Analyze bundle stats**: `npm run stats`
- **Cleanup** (removes `dist`): `npm run cleanup`

# Development

## Assets

- **Stage**: use `cxa-upload.sh` from any local dir
- **Prod**: releases as step in prod pipeline
  - Deploy assets: `npm run deploy:assets <stage>`
  - This command is part of `build.prod.yml`

# Footnotes

## License

- MIT License

## Authors

* **James Blume** - [Crenexi](https://github.com/crenexi)

[urlFlyProd]: https://fly.crenexi.com
[urlFlyStage]: https://stage-fly.crenexi.com
[urlCrenexiFav]: https://www.crenexi.com/assets/brand/fav_48x48.png
