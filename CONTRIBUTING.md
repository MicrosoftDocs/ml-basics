# Contributing to ML Basics

Thank you for your interest in contributing to the **ML Basics** repository! This repo contains exercise notebooks for the [Create machine learning models](https://learn.microsoft.com/training/paths/create-machine-learn-models/) learning path on Microsoft Learn.

This guide covers the contribution process and refers to the [Microsoft Learn contributor guide](https://learn.microsoft.com/contribute/) for more detailed explanations where needed.

## Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Contributor License Agreement (CLA)

Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit <https://cla.opensource.microsoft.com>.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

## How to Contribute

There are several ways to contribute to this project, depending on the type of change you'd like to make.

### Reporting Issues

If you find a bug in a notebook, an error in the instructions, or a broken code example, please [open an issue](https://github.com/MicrosoftDocs/ml-basics/issues/new) in the repository. When filing an issue, please include:

- The name of the notebook (e.g., `01 - Data Exploration.ipynb`).
- A clear description of the problem (what you expected vs. what happened).
- The Python and package versions you are using, if relevant.
- Steps to reproduce the issue.
- Any error messages or tracebacks, formatted as code blocks.

Search the [existing issues](https://github.com/MicrosoftDocs/ml-basics/issues) before creating a new one to avoid duplicates.

### Suggesting Enhancements

Feature requests and suggestions for improving the notebooks are welcome. Please open an issue describing your idea, including:

- What the enhancement would accomplish.
- Which notebook(s) it affects.
- Why it would benefit learners following the Microsoft Learn path.

For larger changes or new notebooks, open an issue with a proposal **before** starting work so the maintainers can confirm it fits the scope of the learning path.

### Making Code Changes

#### Prerequisites

Before contributing code, ensure you have the following set up:

- A [GitHub account](https://github.com/join).
- [Git](https://git-scm.com/) installed locally.
- A Python environment (3.8+) with [Jupyter](https://jupyter.org/) installed.
- Familiarity with the notebook dependencies listed in the repo (NumPy, Pandas, Matplotlib, Scikit-learn, PyTorch, etc.).

#### Fork and Clone

1. Fork the repository to your GitHub account.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/ml-basics.git
   cd ml-basics
   ```
3. Add the upstream remote:
   ```bash
   git remote add upstream https://github.com/MicrosoftDocs/ml-basics.git
   ```

#### Create a Branch

Create a descriptive branch for your changes:

```bash
git checkout -b fix/notebook-typo-01
```

Use prefixes like `fix/`, `feature/`, or `docs/` to indicate the type of change.

#### Make Your Changes

- **Notebooks**: Ensure all cells execute cleanly from top to bottom with a fresh kernel (Kernel → Restart & Run All). Clear all cell outputs before committing so diffs remain readable.
- **Markdown / documentation**: Follow the existing style and tone used in the notebooks and `README.md`.
- **Data files**: Do not add large data files to the repository. If a notebook requires data, use a download step within the notebook itself or reference an existing dataset already included.

#### Commit Guidelines

- Write clear, concise commit messages describing the change.
- Reference related issues where appropriate (e.g., `Fixes #42`).
- Keep commits focused — one logical change per commit.

#### Submit a Pull Request

1. Push your branch to your fork:
   ```bash
   git push origin fix/notebook-typo-01
   ```
2. Open a pull request against the `master` branch of `MicrosoftDocs/ml-basics`.
3. Fill out the PR description with:
   - A summary of the changes.
   - Which notebooks or files are affected.
   - A link to any related issue(s).
4. Ensure the CLA bot check passes and sign the CLA if prompted.

## Pull Request Guidelines

To help us review your PR efficiently:

- **Keep PRs small and focused.** One fix or feature per PR. Avoid combining unrelated changes.
- **Do not submit PRs for style-only changes** (e.g., reformatting code that doesn't fix a bug or improve clarity).
- **Test your changes.** Run the affected notebooks end-to-end before submitting.
- **Respect the existing code style.** Follow the patterns, naming conventions, and commenting style already present in the notebooks.
- **Clear notebook outputs.** Committed notebooks should have cleared outputs to keep diffs manageable.
- **Be responsive.** Maintainers may request changes during review — please respond in a timely manner.

## Notebook Standards

When contributing to or modifying notebooks, please follow these conventions:

- **Narrative flow**: Each notebook is designed to be followed as a self-paced exercise. Maintain clear markdown explanations between code cells so learners understand both what the code does and why.
- **Dependencies**: Only use packages that are available in the standard Azure ML compute environment or that are already used in the repo. If a new dependency is necessary, justify it in your PR.
- **Reproducibility**: Use fixed random seeds where applicable so that results are consistent across runs.
- **Accessibility**: Use descriptive axis labels, titles, and legends in all visualizations. Avoid relying solely on color to convey information.

## Review Process

After you submit a PR:

1. The CLA bot verifies your contributor license agreement.
2. A maintainer will review your changes, typically within a few business days.
3. You may receive feedback or change requests — please address them by pushing additional commits to your branch.
4. Once approved, a maintainer will merge the PR.

Please note that the maintainers reserve the right to close PRs that do not align with the scope of the learning path or that do not meet the quality standards described above.

## Legal Notices

Microsoft and any contributors grant you a license to the documentation and other content in this repository under the [MIT License](https://github.com/MicrosoftDocs/ml-basics/blob/master/LICENSE), and grant you a license to any code in the repository under the [MIT License](https://github.com/MicrosoftDocs/ml-basics/blob/master/LICENSE).

Microsoft, Windows, Microsoft Azure, and other Microsoft products and services referenced in the documentation may be trademarks or registered trademarks of Microsoft in the United States and/or other countries. The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks. Microsoft's general trademark guidelines can be found at <https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks>.

Privacy information can be found at <https://privacy.microsoft.com/>.

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents, or trademarks, whether by implication, estoppel, or otherwise.

## Questions?

If you have questions about contributing that aren't covered here, feel free to [open an issue](https://github.com/MicrosoftDocs/ml-basics/issues/new) and we'll do our best to help.
