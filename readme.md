# DevDiv China Onboarding Site

This repository hosts the source codes of [DevDiv China onboarding site](https://devdivchina.azurewebsites.net/onboarding/intro.html).


## Build & Deploy
[Docfx](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html) is the tool to build the readme files in directory `onboarding/` and generate the html resources in directory `_site/`. The static html files are then hosted in a [WebApp](https://ms.portal.azure.com/#@microsoft.onmicrosoft.com/resource/subscriptions/bead59b7-f469-4601-803a-790729c5213d/resourceGroups/ddc-onboarding-infra).

Building and deployment is triggered manually and on-demand. 
```
// clone the repo
git clone https://github.com/VSChina/onboarding-site

// go to the root folder of the project
cd onboarding-site/

// build the readme files to generate the htmls
docfx build

// host the site locally to preview your changes. The vscode extension `LiveServer` might help.

// deploy the htmls to the webapp
az webapp up -g ddc-onboarding-infra -l eastus -p devdivchina-plan -n devdivchina --html
```

## Contribute
Open a pull request to contribute the site, and add @yungez, @houk-ms as the reviewers. Feel free to reach out to yungez@microsoft.com, honc@microsoft.com for anything questions or suggestions.
