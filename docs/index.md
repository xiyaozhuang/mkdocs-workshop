---
hide:
  - navigation
---

# Workshop activity

## Setup :wrench:

1. Create a new public GitHub repository with a `README.md` and `.gitignore` file.

2. Clone the repository.

3. Create and activate a new virtual environment - see [our guide](https://nhsdigital.github.io/rap-community-of-practice/training_resources/python/virtual-environments/venv/) for details.

4. Install MkDocs with the `pip install mkdocs` command.

5. Initialise an MkDocs project with the `mkdocs new .` command.

## Usage :computer:

1. Preview the website with the `mkdocs serve` command. The preview will refresh on save if file changes are detected.

2. Update the default `docs/index.md` file with any content of your liking.

3. Update the `mkdocs.yml` file with a new site name.

4. Add new content by creating new directories and Markdown files in the `docs` directory.

5. Point to your new files in the `mkdocs.yml` file using the following syntax:

        nav:
          - index.md
          - example.md

## Deployment :rocket:

1. Commit and push changes.

2. Build and deploy static site files using the `mkdocs gh-pages` command.

That's it! Your project will be built and pushed to a new branch `gh-pages` and a GitHub Action will start which you can view in your GitHub repository.

Your site will be available at the `<username>.github.io/<repository-name>` domain name.

## Bonus activities :star:

The content below is outside the scope of this workshop however, if we have time and for those of you that get ahead and would like to explore some more advanced features, give these tasks a go!

- Explore themes! MkDocs also comes with a [Read the Docs](https://docs.readthedocs.io/en/stable/index.html) theme but there are many third-party themes to check out such as [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) which is used here.

- Add social links! For example, I have linked my GitHub in the footer of the site.

- Custom homepage! This task is a bit more advanced and I would recommend looking into [overriding template blocks](https://www.mkdocs.org/user-guide/customizing-your-theme/) for more details.
