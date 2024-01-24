# The Maestro Project - Blogify

## Overview

Welcome to The Maestro Project - Blogify! This repository contains essential information and guidelines for understanding and contributing to our project. Please read through this README to familiarize yourself with our Definitions Of Done (DoD) and find links to our frontend and backend repositories.

## Definitions Of Done (DoD)

The Definitions Of Done (DoD) for our project are aligned with the professor's requirements:

1. **Authentication & Authorization System:**
   - a) Visitors can access the blog without authentication.
   - b) Users must be logged in to publish an article.

2. **Data Collection:**
   - Implement a robust system for collecting and managing data.

3. **Recommendation System:**
   - Develop a recommendation system to enhance the user experience.

## Project Repositories
The project is divided in two parts :
- the backend repository : which uses the Java Spring Boot framework and Postgresql with POJA.
- the frontend repository : coded with React Typescript and uses Tailwind CSS, shadcn UI components, react-router etc..

### Backend Repository

Our backend logic and API are housed in the following repository:

[Blogify API Repository](https://github.com/blogify-app/blogify-api)
#### How to use the app ?
The principle of POJA is that it deploys directly the application So you can check in the Github Actions and search for the deployed app link.

### Frontend Repository

The frontend, responsible for the user interface, is located in the following repository:

[Blogify Web Repository](https://github.com/blogify-app/blogify-web)
#### How to use the app ?
Those are the requirements : 
- Have a recent version of Node JS
- Get yarn

All you have to do is :
- Clone the repository
- Install the packages with `yarn install`
- Run `yarn dev` if you want to see qht it looks like.
- Here are some commands you can use to execute some taska in our project :
```javascript
"scripts": {
    "dev": "vite",
    "build": "tsc && vite build",
    "lint": "eslint . --ext ts,tsx --report-unused-disable-directives --max-warnings 0",
    "format": "prettier --write .",
    "format:check": "prettier --check .",
    "preview": "vite preview",
    "gen-cmp": "shadcn-ui add",
    "test:e2e": "cypress run --spec cypress/e2e/**/*",
    "test:unit": "cypress run --component",
    "test:open": "cypress open",
    "test:e2e:ci": "concurrently \"yarn dev\" \"yarn test:e2e\"",
    "test:ci": "test:unit && test:e2e:ci"
  },
```

However, you don't really need to do all of this to see what our app looks like, here is the link of the deployed app : 
[[https://vercel-prod.vercel.app/](https://blogify-prod.vercel.app/)]

### Upcoming Features
- Recommandation system AI
- Blogify posts list
- A more structured and well designed Blogif
   
## Known Issues

Help us to find bugs !
Put it in the issues of each project-part :
- [https://github.com/blogify-app/blogify-web/issues](https://github.com/blogify-app/blogify-web/issues)
- [https://github.com/blogify-app/blogify-api/issues](https://github.com/blogify-app/blogify-api/issues)

## How to Contribute

We welcome contributions from the community! If you're interested in contributing to our project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and ensure they meet the Definitions Of Done.
4. Test your changes thoroughly.
5. Create a pull request, detailing the changes you've made.

## Getting Help

If you have any questions or need assistance, feel free to reach out to us through the project's GitHub issues.

Thank you for being a part of The Maestro Project - Blogify! 🚀
