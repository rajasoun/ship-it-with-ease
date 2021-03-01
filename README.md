# Ship It with Ease! 🚀

🚀 Collection of tools that performs git hooks management for linting, code formating, commit message standardization, sutomated versioning and package publishing

-   [husky](https://github.com/typicode/husky): Tool that adds scripts (hooks) trigged before (pre-commit) and after (post-commit) your commit.
-   [commitizen](https://github.com/commitizen/cz-cli): Tool that guides the developer through the writing of the commit message
-   [commitlint](https://github.com/conventional-changelog/commitlint): Tool that validates the commit message following a set of rules and good practices
-   [prettier](https://prettier.io/): An opinionated code formatter
-   [lint-staged](https://github.com/okonet/lint-staged): Run linters against staged git files and don't let :poop: slip into your code base!
-   [pre-commit](https://pre-commit.com/): A framework for managing and maintaining multi-language pre-commit hooks
-   [release-it](https://github.com/release-it/release-it): CLI tool to automate versioning and package publishing related tasks

## Prerequisites

1.  Set up your environment.
    The steps include:

        - npm       - v7.6.0
        - Nodejs    - v15.10.0
        - python3   - v3.9.2

1.  Clone this repository:

    ```
    git clone ghttps://github.com/rajasoun/ship-it
    cd ship-it
    ```

1.  To enable husky, commitzen, commitlint, prettier and lint-staged

    ```
    npm install
    ```

1.  To enable pre-commit (python based) and ggshield

    ```
    pip3 install pipenv
    pipenv shell
    pipenv install
    ```

1.  Populate .env file with GITHUB_TOKEN, GITGUARDIAN_API_KEY and GITGUARDIAN_API_URL
    ```
    cp .env.sample .env
    ```
