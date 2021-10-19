# Goal 1: Create cloud resources and deploy the website

Many developers use templates or other samples to help bootstrap their projects. Rather than building from scratch, the pet shelter wants to minimize the startup steps where possible. They would like your team to use a [pre-built template](https://github.com/staticwebdev/mongoose-starter) for [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview?WT.mc_id=academic-28005-chrhar), and configure the cloud resources necessary to host the template.

## The goal

For this goal, your team will deploy a [template built for Azure Static Web Apps](https://github.com/staticwebdev/mongoose-starter). The template includes:

- Client app written with HTML, CSS and vanilla JavaScript
- Server-side code using [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview?WT.mc_id=academic-28005-chrhar) and [Mongoose](https://mongoosejs.com/) to interact with the database

Your team will also create and configure the following resources on Azure to host the project:

- Azure Static Web App to host the project
- [Azure Cosmos DB API for MongoDB](https://docs.microsoft.com/azure/cosmos-db/mongodb/mongodb-introduction?WT.mc_id=academic-28005-chrhar) to store the data

## The Azure Services

[Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview?WT.mc_id=academic-28005-chrhar) is a service which builds and deploys full stack web apps to Azure from a code repository. It provides hosting for static files (HTML, CSS, JavaScript, etc.) and server-side code through serverless Azure Functions. Azure Static Web Apps can host applications written with any front-end framework, including React, Angular, Vue.js and Svelte. Azure Functions can be used to access server resources such as databases or other APIs. A site deployed to Azure Static Web Apps automatically scales, and can even have custom domains.

Deployment is managed through [GitHub actions](https://github.com/features/actions). When you create a static web app, Azure will automatically create a workflow file on your GitHub repository. This allows you to use GitHub just as you normally would, and updates to *main* or whatever branch you specify are automatically deployed to Azure.

Finally, [Azure Cosmos DB API for MongoDB](https://docs.microsoft.com/azure/cosmos-db/mongodb/mongodb-introduction?WT.mc_id=academic-28005-chrhar) will be the database for the project. Cosmos DB supports different APIs, including MongoDB API allowing for flexibility in application development. Because the database supports MongoDB API you can use a client such as [Mongoose](https://mongoosejs.com/) or the [MongoDB Node Driver](https://docs.mongodb.com/drivers/node/current/).

## Application notes

Your team will use the [Static Web Apps - Mongoose starter](https://github.com/staticwebdev/mongoose-starter) as the base for the shelter's site. You will find documentation about the template on the repository, and the code is heavily commented.

## Success criteria

Your team will work together to deploy the application to Azure using Azure Static Web Apps. Your team will have achieved this goal when the following success criteria are met:

- The site has been successfully deployed to Azure Static Web Apps
- You can open the index page, authenticate via GitHub, create a task and mark it as completed

## Tips

- **DO NOT** delete the resource group after walking through the tutorial; you'll be using the deployed project for the remainder of the workshop.

## Resources

These resources should help provide your team with the necessary information to accomplish the goal:

- [What is Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview?WT.mc_id=academic-28005-chrhar)
- [Tutorial: Access data in Cosmos DB using Mongoose with Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/add-mongoose?WT.mc_id=academic-28005-chrhar)

## Validation

To validate your team's work with the [automated tool](https://ashy-mushroom-0609d7c10.azurestaticapps.net/), enter the newly created URL on Azure Static Web Apps into the tool.

## Final result

After deploying the project you can now perform the following tasks:

1. Navigate to the site
1. Login using GitHub
1. Add a new task (maybe named Test)
1. Mark the task as completed

![Screenshot of the application after login with a username of GeekTrainer and a task of Test](./media/tasks.png)

## Next challenge

Once you've deployed your application, it's time to [run the site locally](./2-local.md).
