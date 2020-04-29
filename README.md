# Accord Project Web Components

This repository contains a library of user interface components that can be used to create web-applications based on Accord Project technology. The components use the [React](https://reactjs.org) web application framework.

Use the interactive [Storybook](https://accordproject.github.io/web-components) for the components to discover their properties.

## Repository Structure

This repository is a monorepo, built using [lerna](https://lerna.js.org). The packages have all been created using the `create-react-library` npm module.

The `storybook` package is a [React Storybook](https://storybook.js.org), and contains all the stories for all the sub-packages, as well as some external packages.

GitHub Actions is used to automatically publish the static site generated by Storybook to GitHub pages.