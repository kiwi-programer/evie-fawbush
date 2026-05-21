# evie-fawbush

## Deploy to Vercel

This is a simple static site. You can deploy it to Vercel in two ways:

- **Via the Vercel dashboard:** Connect this GitHub repository in the Vercel dashboard and deploy.
- **Via GitHub Actions (automatic on push to `main`):** The repository includes a GitHub Actions workflow at [.github/workflows/vercel-deploy.yml](.github/workflows/vercel-deploy.yml) that deploys to Vercel when commits are pushed to `main`.

To enable the GitHub Actions deployment, add the following secrets in your repository settings:

- `VERCEL_TOKEN` — a Vercel personal token (create one at https://vercel.com/account/tokens).
- `VERCEL_ORG_ID` — your Vercel organization ID.
- `VERCEL_PROJECT_ID` — your Vercel project ID.

Once the secrets are set, push to `main` and the workflow will deploy the site to Vercel.

## Images

Place site images in [assets/images](assets/images). A short list of recommended filenames lives in [assets/images/README.md](assets/images/README.md).
