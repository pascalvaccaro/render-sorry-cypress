# Sorry (render) Cypress

Running sorry cypress on render, for a fraction of the cost of other platforms.

In this repo, the sorry cypress stack is deployed using render.

## Deployment

Use this repo, or copy the render.yaml.

## Test locally

Run the following command to start the Dashboard locally ([documentation](https://docs.sorry-cypress.dev/guide/dashboard-and-api))

```
docker-compose -f ./docker-compose.yml up
```

## Usage

You need to give the external URL of the `director` service from Render to the process running `cy2` as an environment variable named `CYPRESS_API_URL` ([documentation](https://docs.sorry-cypress.dev/guide/get-started))

Next, navigate to the external URL of the `dashboard` service from Render and follow the creation steps.

### Cypress configuration

Your Cypress configuration must include a `projectId` matching the one you created in the Sorry Cypress Dashboard
