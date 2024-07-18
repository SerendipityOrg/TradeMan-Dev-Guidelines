---
hide:
    - footer
---
# Setting Up a New Project

## 🚀 Step 1: Create a New Github Project

1. Go to [Github](https://github.com) and create a new **Project**.
2. Name the project and provide a brief description.
3. Choose the project visibility (public or private).
4. Add a project description and link any relevant repositories.

**Checklist:**

- [ ] Github Project created for project management

## 🏗️ Step 2: Create Repos from Templates and Iterate on Ideation Worksheet

1. Go to the [templates repositories page](/new-project-kit/templates_repos/) and click on the docs repository.
2. Click on the "Use this template" button on Github.
3. Choose a name for the new repository and click on "Create repository from template".
4. Create a [docs repository]() first by clicking on the "Use this template" button on Github for the docs template repository.
5. Use the [Ideation worksheet](/new-project-kit/docs-template/docs/project-docs/discovery_and_ideation_worksheet_template/) to iterate and finalize on the features and fill up the PRD & TDD.
6. Lastly, repeat the process for each template repository you need (e.g. code repositories like flutter-app, react-app, react-admin-app, backend, etc.).

**Checklist:**

- [ ] Docs repository created
- [ ] Ideation worksheet is filled up with features and the PRD & TDD are updated
- [ ] All other template repositories created for project development

## 💻 Step 3: Setup CI/CD

1. Go to [Github Actions](https://github.com/features/actions) and enable Github Actions for your project.
2. Create a new workflow file in the `.github/workflows` directory of your repository.
3. Choose a suitable workflow template for your project (e.g., Flutter, React, Node.js, etc.).
4. Customize the workflow file according to your project's needs.
5. Commit and push the workflow file to your repository.
6. Github Actions will automatically run the workflow on every push to the default branch.
7. Configure additional workflows as needed (e.g., for testing, deployment).

**Checklist:**

- [ ] Github Actions enabled
- [ ] Workflow file created and committed
- [ ] Additional workflows configured (if needed)

