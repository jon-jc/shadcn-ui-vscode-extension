# Contributing

We're grateful for your interest and efforts in contributing to this project! Your participation is invaluable to us, and we aim to make the contribution process as smooth as possible. Please review the following guidelines before contributing to ensure effective collaboration. Together, we can enhance this project and contribute to its success!

## Open Development

Development takes place on GitHub. Contributions are made through pull requests, which are reviewed following the same code review process for both core team members and external contributors.

### Credits

All credits go to these amazing developers

-[Selemondev](https://github.com/selemondev/vscode-shadcn-vue) for creating the Shadcn vue extension.

- [Shadcn UI](https://ui.shadcn.com) for creating this beautiful project.
- [Shadcn Vue](https://shadcn-vue.com) for creating the Vue port of Shadcn UI.
- [Radix Vue](https://radix-vue.com) for doing all the hard work to make sure components are accessible.
- [VueUse](https://vueuse.org) for providing many useful utilities.
- [Suhel Makkad](https://github.com/SuhelMakkad/vscode-shadcn-ui) for creating the Shadcn UI VSCode extension.
- [Neeraj Dalal](https://github.com/nrjdalal/shadcn-ui-snippets) for creating the Shadcn UI Snippets VSCode extension.

## Semantic Versioning

We adhere to semantic versioning principles. This means patch releases address bugs and non-breaking changes, minor releases introduce backward-compatible new features, and major releases introduce changes that might break backward compatibility.

Significant changes are documented in the changelog.

## Reporting Issues

If you find any bugs or have suggestions for improvement, please submit them through [GitHub issues]

Before reporting, please:

1. **Search for Similar Issues**: Check if the issue or feature request has already been reported or discussed.
2. **Reproduce the Bug**: Provide steps or a minimal code example to replicate the issue.
3. **Describe Feature Requests**: Clearly describe the desired feature and its context.

Adhering to these guidelines ensures a more organized and efficient resolution process.

## Commit Guidelines

Your commit messages should follow the [conventional-changelog standard](https://www.conventionalcommits.org/en/v1.0.0/):

````bash
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```markdown
<p align="center">
 <h1 align="center">
  Your Project Name
 </h1>
</p>

This extension allows direct installation of shadcn components into your IDE, streamlining your development workflow.

## Getting Started

1. **Initialize the CLI**: Open the command palette and search for `shadcn: install cli` to set up the CLI.


2. **Install Components**: Search for `shadcn: add new component` to add components to your project.


3. **Choose and Install Multiple Components**: Select multiple components from the list to install.



4. **Access Documentation**: Quickly open the Shadcn documentation for reference.


5. **Navigate Component Documentation**: Directly access specific component documentation.


## Shadcn Snippets

Enhance your coding efficiency with shadcn snippets. Type `cn` or `shadcn` and select from the snippet options to use components within your files.



### Usage

Type `cni-[component]` to add imports and `cnx-[component]` for using a component in your files. For example:

- To use the `Alert` component, type `cni-alert` to add imports and `cnx-alert` to integrate the component.

```tsx
// cni-alert
import {
````
