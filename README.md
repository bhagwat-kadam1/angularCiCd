# AngularCiCd

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 21.2.19.

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

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## CI/CD and GitHub Pages

The GitHub Actions workflow runs unit tests and a production build for pull
requests targeting `main` and pushes to `main`. On a successful push to `main`,
it builds and deploys the app to four paths on the repository's GitHub Pages
site:

- `/dev/`
- `/test/`
- `/stage/`
- `/prod/`

Each path is a separately built Angular app with its base URL configured for
that path. All four paths are published together from the same `main` commit.
The site root redirects to `/prod/`.
For this repository, the URLs are:

- https://bhagwat-kadam1.github.io/angularCiCd/dev/
- https://bhagwat-kadam1.github.io/angularCiCd/test/
- https://bhagwat-kadam1.github.io/angularCiCd/stage/
- https://bhagwat-kadam1.github.io/angularCiCd/prod/

To enable deployment, open the repository's **Settings > Pages** and set the
build and deployment source to **GitHub Actions**.

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
