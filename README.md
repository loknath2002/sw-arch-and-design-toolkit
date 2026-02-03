# Software Architecture and Design Toolkit (SAD-TK)

![Deployment](https://github.com/loknath2002/sw-arch-and-design-toolkit/actions/workflows/Deploy.yml/badge.svg)

A handy toolkit for software engineers, architects, and developers to design effective software. It brings together software patterns, best practices, and practical examples all in one place.

> [!TIP]
> [Browser the toolkit here](https://quantum-technology.in/software/arch-design-toolkit/)

## Contribution

To [contribute](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project), fork the repository and create a pull request from a branch in your fork.

## Adding a new document/topic

1. All the documents are placed under `/docs` following the typical [Docusaurus](https://docusaurus.io/docs/next/create-doc) pattern. Familiarize yourself with the directory structure.
2. Look for the right directory to place the new document under.
3. Copy the file `template.mdx` (root of the repo) to the identified target directory in `/docs`.
4. Rename the file and contents as per the topic. Set up a [local development](#local-development-and-testing) environment to test the changes as you edit the document.
5. Upon completion, submit a pull request. 🥳.

## Local Development and Testing

The repository uses [Docusaurus](https://docusaurus.io/) and the basic requirements are **node(20.0 or above) and npm**

### One time task

Upon a fresh clone of the project, dependencies must be installed. In order to do that, navigate to the repo directory and run the following.

``` bash
npm install
```

### Testing locally

In order to test the changes, a development server is required. ```npm run start``` will start a development server. This server will automatically reload the data when a change is saved. The server usually runs @`http://localhost:3000/software/arch-design-toolkit/` whenever 

## Deployment

Upon the approval of the pull request, the changes will be deployed automatically.

