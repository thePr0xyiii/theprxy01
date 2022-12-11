<p align='center'>
  <img src='https://ibb.co/VjJHkCS' alt='picture' width='600'/>
</p>

# Prxy

[![]()]()

stuff on here:

- 
- 
- 
- 
-
- 
- 
- 
- 

## Getting Started

Scaffold this repository

```sh
pnpx degit lecoueyl/vue3-template my-project
cd my-project
```

Install and start dev server

```sh
pnpm install
pnpm run dev
```

## Deployment

### Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/lecoueyl/vue3-template)

### Github pages

The default github action will build to `gh-page` when pushing on `main` branch.

For a project page, the base path of the repository must be specified. Add the following secret in the Github repository Settings > Secrets > Actions

| Name                        | Value                    |
| --------------------------- | ------------------------ |
| VITE_BASE_PUBLIC_PATH       | `/repository-name/`      |
