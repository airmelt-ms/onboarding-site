# DevDiv China Onboarding Site

This repository hosts the source codes of [DevDiv China onboarding site](https://devdivchina.azurewebsites.net/onboarding/intro.html).


## Contribute
You're welcomed to contribute to the site! 

[Docfx](https://dotnet.github.io/docfx/tutorial/docfx_getting_started.html) is the tool to build the readme files in directory `onboarding/` and generate the html resources in directory `_site/`. The static html files are then hosted in a [WebApp](https://ms.portal.azure.com/#@microsoft.onmicrosoft.com/resource/subscriptions/bead59b7-f469-4601-803a-790729c5213d/resourceGroups/ddc-onboarding-infra). Building and deployment now is scheduled manually and on-demand.

Follow the steps here to contribute to the site.

```
// 1. clone the repo
git clone https://github.com/VSChina/onboarding-site

// 2. go to the root folder of the project
cd onboarding-site/

// 3. contribute your contents by modifying the readme files in onboarding/ folder

// 4. build the readme files to generate the htmls
docfx build

// 5. host the site locally to preview your changes (vscode extension `LiveServer` might help).

// 6. open a pull request to the repository, and add @yungez, @houk-ms as the reviewers

// 7. @yungez, @houk-ms will merge and deploy your commits.
```

Feel free to reach out to yungez@microsoft.com, honc@microsoft.com for anything questions or suggestions about the site.
