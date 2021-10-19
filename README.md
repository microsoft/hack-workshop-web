# Scenario : The Pet Shelter

According to the American Society for the Prevention of Cruelty to Animals (ASPCA), animal shelters receive about 3 million dogs annually - about 6 dogs per minute! While euthanasia rates have dropped, over 500,000 dogs are euthanized because they could not be matched with their original owners or an adoptive family.

Your team will assist a fictional pet adoption agency in creating a website. To start they would like to provide a tool where a user could create a list of all the tasks they need to perform when they adopt a pet, like schedule their first vet appointment or apply for a dog license. Your team will do so by using [Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/overview?WT.mc_id=academic-28005-chrhar) for hosting and an already created template.

## Prerequisites

### Azure account

Each team member will need an Azure account. With [Azure for Students](https://aka.ms/a4s?WT.mc_id=academic-28005-chrhar), you can access $100 in free credit, and a large suite of free services!

### Skills

- HTML, CSS and JavaScript
- Git and GitHub
  - [Forking](https://docs.github.com/github/getting-started-with-github/quickstart/fork-a-repo) and [cloning](https://docs.github.com/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) repositories
  - [Creating and managing branches](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches)

### Software

- [Git](https://git-scm.com/downloads)
  - [Install git on macOS](https://git-scm.com/download/mac)
  - [Install git on Windows](https://git-scm.com/download/win)
  - [Install git on Linux](https://git-scm.com/download/linux)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Node.js](https://nodejs.org/)
  - [Install Node.js on Windows](https://docs.microsoft.com/windows/dev-environment/javascript/nodejs-on-windows?WT.mc_id=academic-28005-chrhar)
  - [Install Node.js on Linux or MacOS](https://github.com/nvm-sh/nvm#installing-and-updating)
- [Azure Functions Core Tools](https://www.npmjs.com/package/azure-functions-core-tools), which can be installed by running the following command (after Node.js and npm are installed)

  ```bash
  npm i -g azure-functions-core-tools@3 --unsafe-perm true
  ```

## Resources

A series of resources will be provided to help your team determine the appropriate steps for completion. The resources provided should provide your team with enough information to achieve each goal. If you get stuck, you can always ask a mentor for additional help.

A [sample of the site](https://kind-beach-04aea671e.azurestaticapps.net/) has been deployed so you can see how it looks in action.

## Goals

Your team will obtain the starter, deploy the application to the cloud, download and run the source code locally, and make modifications to the site.

1. [Obtain and deploy the template to the cloud](./goals/1-deploy.md):
   Because the pet shelter wants the application to be publicly available, your team will need to deploy the application. For this workshop, your team will use Azure Static Web Apps, which is able to host the application and run the Azure Functions.
1. [Download and run the application locally](./goals/2-local.md):
   After creating the project on GitHub and deploying it to Azure Static Web Apps, each member of your team will download the project and run it locally for development purposes.
1. [Modify the site and push updates](./goals/3-modify.md):
   The template uses a relatively generic example of a task management system. You want to update the landing page to display a proper welcome message and update the verbiage to include the suggested usage - tracking what the pet adopter needs to do post adoption.

## Validation

This workshop is designed to be a goal-oriented self-exploration of Azure and related technologies. Your team can use the [validation tool](https://ashy-mushroom-0609d7c10.azurestaticapps.net/) to confirm the site has been deployed correctly and updates pushed.

## Where do we go from here?

This project is designed as a potential seed for future development. From a technical perspective, you can begin to incorporate whatever frameworks or technologies you wish to use. This could include [React](https://docs.microsoft.com/learn/paths/react?WT.mc_id=academic-28005-chrhar) or [Vue](https://docs.microsoft.com/learn/paths/vue-first-steps/?WT.mc_id=academic-28005-chrhar).

If you were to continue with this idea, your team could potentially:

- Use the [Petfinder API](https://www.petfinder.com/developers/) to create an application to match potential adopters with dogs
- Use the [Bing Maps API](https://docs.microsoft.com/bingmaps/getting-started/?WT.mc_id=academic-28005-chrhar) to search based on location
- Use [Custom Vision](https://azure.microsoft.com/services/cognitive-services/custom-vision-service/?WT.mc_id=academic-28005-chrhar) to identify dog breeds

## Additional notes and disclaimers

### Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

### Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party's policies.
