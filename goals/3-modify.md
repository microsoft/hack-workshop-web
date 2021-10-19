# Goal 3 - Modifying the site

Congratulations on setting up the project for local development! Now that everyone on your team has a copy running locally it's time to make some modifications to the code.

Because the shelter wants to allow adopters to use the site to manage tasks related to pet adoption, they would like to update the site. They want the header to reflect the purpose of the site, for managing a list of tasks for pet adoption.

## The goal

Your team will complete this workshop by making and deploying a modification to the site. The header text needs to be updated to read "Pet Adoption Tasks" and the changes pushed to Azure.

## The Azure Service

Azure Static Web Apps uses [GitHub Actions](https://docs.microsoft.com/azure/static-web-apps/build-configuration?tabs=github-actions&WT.mc_id=academic-28005-chrhar) to manage deployment. Whenever a pull request (PR) or merge is made into the main branch the action is triggered and a new deployment starts. If code is merged into the branch, the deployment is pushed to the production site; PRs [generate a new staging environment](https://docs.microsoft.com/azure/static-web-apps/review-publish-pull-requests?WT.mc_id=academic-28005-chrhar).

## Application notes

The client files are contained in the **public** folder. **index.html** is the HTML used to display the index page on the site.

## Success criteria

To successfully complete this goal, your team will:

- Update the `h1` header on the index page to read **Pet Adoption Tasks**
- Redeploy the site to Azure Static Web Apps

## Tips

A good habit to get into when modifying code is to create a new branch, make modifications, create a PR into the main branch, and then merge. However, for this workshop you can push straight to main.

## Resources

Your team might find these resources helpful:

- [Review pull requests in pre-production environments in Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/review-publish-pull-requests?WT.mc_id=academic-28005-chrhar)

## Validation

To validate your team's work with the [automated tool](https://ashy-mushroom-0609d7c10.azurestaticapps.net/), re-enter the URL on Azure Static Web Apps into the tool.

## Congratulations

Congratulations on successfully completing the workshop! Your team now has a template and deployment model to use for creating a website. If you wish to continue to explore Azure Static Web Apps:

- [Set up a custom domain with free certificate in Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/custom-domain?tabs=azure-dns?WT.mc_id=academic-28005-chrhar)
- [Troubleshooting deployment and runtime errors](https://docs.microsoft.com/azure/static-web-apps/troubleshooting?WT.mc_id=academic-28005-chrhar)
- [Publish an Angular, React, Svelte, or Vue JavaScript app with Azure Static Web Apps](https://docs.microsoft.com/learn/modules/publish-app-service-static-web-app-api?WT.mc_id=academic-28005-chrhar)
