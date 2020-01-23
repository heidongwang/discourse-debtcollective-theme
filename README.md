# debtcollective-theme

This project has been based upon the structure generated by [Discourse Theme CLI](https://meta.discourse.org/t/discourse-theme-cli-console-app-to-help-you-build-themes/82950) to hold all customization needed for the custom debtcollective community _(all customisation that fits within the Theme scope)_.

If you want to know more about themes, themes component, widgets and other customisation approaches for Discourse take a look at [Beginner’s guide to using Discourse Themes](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966).

## Customization

This theme expect the community to have set **Categories only** as a homepage, you can achieve that by running setup wizard again visiting `http://localhost:3000/wizard` (for local discourse)

## Development

## Discourse Theme creator

There are different ways to approach this, using a local setup of Discourse and using the [Theme creator](https://theme-creator.discourse.org/) which doesn't need much further setup for you to start the development process but it does need **internet connection to develop**. Check [Beginners’ guide to using Theme Creator and Theme CLI to start building a Discourse theme](https://meta.discourse.org/t/beginners-guide-to-using-theme-creator-and-theme-cli-to-start-building-a-discourse-theme/108444), after complete you should be ready to start.

Once you are set you should be able to run

```shell
cd /path/to/folder_containing_debtcollective-theme
discourse_theme watch debtcollective-theme
```

## Local Discourse installation

This uses the same [Theme CLI](https://meta.discourse.org/t/discourse-theme-cli-console-app-to-help-you-build-themes/82950) as the Theme creator method, but you make the changes against a local Discourse installation.

The steps are the same as above, but when configuring the instance you enter:

1. `http://localhost:3000` as the host
2. API key for your local installation, you can [get them here](http://localhost:3000/admin/api/keys). Make sure to create it just for your user only.

### VSCode

There are a few covenient plugins you may want to add if you are using VSCode. [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint), [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode), [Stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint), [Stylefmt](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-stylefmt) those in order to make sure you have automatic fix over the code.

## Resources

There is a complete guide to onboarding you within the Discourse customisation world at [Developer’s guide to Discourse Themes](https://meta.discourse.org/t/developer-s-guide-to-discourse-themes/93648)
