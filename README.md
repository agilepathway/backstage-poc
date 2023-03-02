# backstage-poc
Example [Backstage](https://backstage.io) app

## Development environment

The recommended development environment is a [GitHub Codespace](https://github.com/features/codespaces),
as this will configure everything for you in minimal time.  All you need to do is 
[create a Codespace from this repo](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository). When you create your
Codespace, it's recommended to give it no less than 8GB of RAM, to avoid out of memory problems.

## Run the app

The Backstage app files in this repo were generated by running `npx @backstage/create-app@latest`, as per
[the instructions in the Backstage getting started guide](https://backstage.io/docs/getting-started/#create-your-backstage-app).

To run the app (as per [the Backstage getting started guide](https://backstage.io/docs/getting-started/#run-the-backstage-app):

- `cd my-backstage-app && yarn dev && cd ../`

- go to http://localhost:3000
  
  NB the app may automatically open the app in the browser with 127.0.0.1 rather than localhost, but if it does then close that browser tab and use the above localhost URL instead (with 127.0.0.1 it cannot load the backend because of [CORS](https://en.wikipedia.org/wiki/Cross-origin_resource_sharing)).
