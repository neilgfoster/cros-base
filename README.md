# base
This is my base template repository I use for all my repositories. It contains some basic structure and setup scripts that I reuse across all my projects.

> [!NOTE]
> Don't forget to update the `-o` and `-r` variables in the setup.sh script after creating a new repository from this template. In addition, update the URL in the "Getting Started" section below.

## Whats Included?

### Code Owners
A CODEOWNERS file is included to define the code owners for the repository, which defaults to myself. This helps in managing code reviews and approvals.

### Setup Scripts
Setup scripts are included to automate the initial setup of a new repository. These scripts can be customized as needed. Supports calling scripts from other repositories that follow the same pattern. Can be executed using bash and curl:
```bash
bash <(curl -sS https://raw.githubusercontent.com/neilgfoster/base/main/.setup/setup.sh) -o=neilgfoster -r=base
```