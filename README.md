# yapy-copier-template

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
