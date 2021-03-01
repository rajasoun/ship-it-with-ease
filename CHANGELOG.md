## Unreleased

### Refactor

-   **package.json cleanup**: clean package.json and simplify
-   **pre-commit doc and npm helper script**: pre-0commit documentation and helper script
-   **change repo to public**: change npm package to public

### Feat

-   **github tags and release**: release-it to manage github tags and release
-   \*\*pre-commit as docker\*\*: pre-commit as docker for simplification of tool dependencies on python
-   **tooling : ggshield as docker**: ggshield secrets detection as docker
-   **tooling : gitguardian**: secrets detection
-   **tooling : pre-commit**: husky and pre-commit together
-   **ship-it : initial checkin**: collection of tools that enables shipping of software at ease

### Fix

-   **revert release-it tool**: reverting back release-it tool
-   **github repository user access**: raja-soundaramourty to rajasoun
-   **pre-push script validation**: validate if ggshield identifies secerts if present
-   **pre-push ggshield fix**: logic change from commit-range to pre-commit
-   **git pre-push fix**: simplified logic
