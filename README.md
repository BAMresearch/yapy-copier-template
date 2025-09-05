# yapy-copier-template (v1.1.11)

Yet Another Python [Copier][1] template for a Python modules and applications focussing on data science, processing and analysis.

[1]: https://copier.readthedocs.io

## Usage

1. In your python environment, install the required packages first. A list is provided in `requirements.txt`:

        pip install -r requirements.txt
    
2. The create a new project scaffolding in the to-be-created directory `my-test-project`, run:

        copier copy yapy-copier-template my-test-project

3. Finally, init version control in that directory:

        cd my-test-project
        git init
        git add -A
        git commit -m "initial import"

4. Optionally, set the remote of the repository to a server where you created this respective project and push the changes up to now:

        git remote add <URL of the repository>
        git push origin --set-upstream main

## Publishing documentation

For the target repository where this template was applied on, first create an empty `gh-pages` branch for publishing. This is how to make an orphan branch with no history and no files initially:

1. Create the orphan `gh-pages` branch (a new root branch with no commit history):

        git switch --orphan gh-pages

2. Remove all tracked files from the staging area and working directory:

        git rm --cached -r .
        git clean -fd

3. Create an initial empty commit (or add minimal files like an empty `index.html`):

        git commit --allow-empty -m "Initial empty gh-pages commit"


4. Push the new branch to GitHub and set it as the upstream branch:

        git push -u origin gh-pages

This creates a clean, empty `gh-pages` branch that you can later add your static site files to for GitHub Pages publishing.

### Summary command sequence:

    git switch --orphan gh-pages
    git rm --cached -r .
    git clean -fd
    git commit --allow-empty -m "Initial empty gh-pages commit"
    git push -u origin gh-pages

After this, on your GitHub repository under **Settings** -> **Pages**, choose the `gh-pages` branch as the source to enable publishing.

This method ensures your `gh-pages` branch is completely separate and empty initially, good for publishing static content without mixing with your main codebase.

## Publishing Python packages

The *publish* job of the GitHub Action Workflows which come with this template will attempt to upload built packages to [PyPI](https://pypi.org) or [TestPyPi](https://test.pypi.org), depending on your choice in the questionaire.

For this to succeed, you will need to create an account on the respective platform and add a new *For this to succeed, you will need to create an account on the respective platform and add a new *Trusted Publisher* via **Your Account** -> **Publishing**. It needs to know the

    - PyPI Project Name, lower case name without spaces, dashes instead of underscore
    - Repository Owner, user or organization where the repo is hosted, `repo_userorg` in `.copier-answers.yml`
    - Repository name, asked for in the questionaire: `repo_name` in `.copier-answers.yml`
    - Workflow name, here it'll be the top-most workflow file `ci-cd.yml`
