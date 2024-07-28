# Create Template

First, install the cookiecutter package using pip via

```shell
pip install cookiecutter
```

Once you've confirmed your installation, you can create the project by running 
```shell
cookiecutter https://github.com/AutoResearch/autora-template-cookiecutter
```

You will be prompted with a series of questions to customize your project. If a prompt displays, `N/A - Press Enter to Skip`, you can skip the question.

- For question **3**: *contribution_name*, provide only the contribution name without the prefix `autora-theorist`.
- For question **6**: *contribution_type*, choose 1 (theorist)
- For question **9**: *advanced_contribution_utilities*, choose 2 (advanced contribution). This will setup GitHub actions and pre-commit hooks
- For question **11**: *use_current_directory*, choose 2 (yes). This will setup the project in the current folder. Make sure that the contribution name and the name of the repository are the same.
