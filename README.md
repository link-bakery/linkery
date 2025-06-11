<center>
  <h1>Your Link-Bakery 🔗🍩🚀</h1>
</center>

![Linkery Banner](./banner.png)

## Getting started 🛫
## Setup Dev-environment 🧑‍💻
- Clone all linkery repos like the following:
```
📂 linkery/
├── 📁 linkery/               # 🔗 https://github.com/link-bakery/linkery
│   └── 📄 example.env
│   └── ...
├── 📁 linkery-backend/       # 🔗 https://github.com/link-bakery/linkery-backend
├── 📁 linkery-docs/          # 🔗 https://github.com/link-bakery/linkery-docs
├── 📁 linkery-frontend/      # 🔗 https://github.com/link-bakery/linkery-frontend
├── 📁 linkery-shared/        # 🔗 https://github.com/link-bakery/linkery-shared
```
- Setup your .env file based on `linkery/example.env`
  
  To run the backend without docker you also have to copy your .env to `linkery/linkery-backend/.env`
- Start the linkery-database service from `linkery/` => `docker compose -f docker-compose.dev.yml start linkery-database`
- Install dependencies for `linkery-backend`, `linkery-frontend`, `linkery-shared` and `linkery-docs` with `npm install`
- To start the linkery-backend run following in `linkery-backend/` => `npm run start:dev` (Here you need the .env copied from `linkery/`)
- To start the linkery-frontend run following in `linkery-frontend/` => `npm run start`
- **Optional and not necessary for development:** To start the linkery-docs run following in `linkery-docs/` => `npm run start` (When you want to run it parralel to linkery-backend start it first and run linkery-docs on port 3001)

## Docs page 📝
[![Netlify Status](https://api.netlify.com/api/v1/badges/cc87bcbd-bfed-4529-b7a4-976969050440/deploy-status)](https://app.netlify.com/projects/linkery-docs/deploys)

The [Linkery documentation](https://linkery.madudev.de/) is based on [Docusaurus](https://docusaurus.io/).
The associated repo is [linkery-docs](https://github.com/link-bakery/linkery-docs)

## Bakers 🧑‍🍳
🦆 [Madu-de](https://github.com/Madu-de)