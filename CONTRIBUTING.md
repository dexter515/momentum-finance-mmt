# Contributing Guidelines for Momentum Finance (MMT) Swap Script

We highly value contributions from the community! By following these guidelines, you'll help us maintain code quality and ensure a smooth contribution process.

## Code of Conduct

Please adhere to our Code of Conduct. We are committed to fostering a welcoming and inclusive environment for all contributors.

## How Can You Contribute?

There are several ways you can contribute to this project:

* **Report Bugs**: If you find a bug, please report it in the [Issues](https://github.com/dexter515/momentum-finance-mmt/issues) section. Provide detailed information and steps to reproduce the bug.
* **Suggest Features**: Have an idea for a new feature? Create an [Issue](https://github.com/dexter515/momentum-finance-mmt/issues) and describe the feature you'd like in detail, along with why it's important.
* **Submit a Pull Request (PR)**: If you want to contribute code (bug fixes, new features, improvements), follow the steps below.

## Setting Up Your Development Environment

1.  **Fork** the repository: Click the "Fork" button in the top right corner of the GitHub page.
2.  **Clone** your forked repository to your local machine:
    ```bash
    git clone [https://github.com/dexter515/momentum-finance-mmt.git](https://github.com/dexter515/momentum-finance-mmt.git)
    cd momentum-finance-mmt
    ```
    (This will be your own forked repository)
3.  **Install dependencies**:
    ```bash
    npm install
    ```
4.  **Configure Environment Variables**:
    * Rename the `env.example` file to `.env`:
        ```bash
        cp env.example .env
        ```
    * Edit the `.env` file in the root directory.
    * Add your Sui wallet mnemonic (use a test wallet for development!):
        ```bash
        SUI_MNEMONIC=your_test_wallet_mnemonic_here
        ```

## Pull Request Workflow

1.  **Create a New Branch**: Create a new branch from the `main` branch for your work. Use a descriptive name for your branch (e.g., `fix/bug-name` or `feat/feature-name`).
    ```bash
    git checkout main
    git pull origin main
    git checkout -b fix/your-bug-name
    ```
2.  **Make Your Changes**: Write your code, fix the bug, or implement the new feature.
3.  **Test Your Changes**: Ensure your changes work as expected and don't introduce regressions. Write tests where possible.
4.  **Commit Your Changes**: Write a clear and concise commit message that explains your changes.
    ```bash
    git commit -m "feat: add feature X"
    git commit -m "fix: fix bug Y in module Z"
    ```
    (Use prefixes like `feat:` for features, `fix:` for bug fixes, `docs:` for documentation changes, etc.)
5.  **Push to Your Repository**:
    ```bash
    git push origin your-branch-name
    ```
6.  **Create a Pull Request**:
    * Go to your repository on GitHub.
    * Click the "Compare & pull request" button that will appear.
    * Provide a clear title and a detailed description of your PR. Explain why your changes are needed and what problem they solve.
    * Link to any relevant issues if applicable (e.g., `Closes #123`).

## Code Guidelines

* Follow the existing code style within the project.
* Write clean, readable, and modular code.
* Add relevant comments if your code is complex.
* Avoid introducing unnecessary dependencies.

## Questions?

If you have any questions about contributing, feel free to open an [Issue](https://github.com/dexter515/momentum-finance-mmt/issues) and we'll be happy to assist you.

Thank you for contributing!
