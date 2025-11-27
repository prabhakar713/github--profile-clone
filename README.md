# GithubProfile

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.19.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Deployment (Vercel)

This repository contains a Vercel configuration and a small serverless wrapper so the application can run with SSR on Vercel.

To enable automatic production deployments from GitHub you need to add the following repository Secrets in GitHub (Repository → Settings → Secrets & variables → Actions):

- VERCEL_TOKEN — create a personal token at https://vercel.com/account/tokens
- VERCEL_ORG_ID — your Vercel organization ID (available in the Vercel dashboard)
- VERCEL_PROJECT_ID — the Vercel project ID (found in project Settings → General)

Once the secrets are configured, pushes to `main` will trigger the `CI / Deploy to Vercel` workflow and automatically publish a production deployment.

