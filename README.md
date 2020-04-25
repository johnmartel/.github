# github settings

[![](https://github.com/johnmartel/.github/workflows/Validate%20YAML%20files/badge.svg)](https://github.com/johnmartel/.github/actions?query=workflow%3A%22Validate+YAML+files%22)
[![](https://api.dependabot.com/badges/status?host=github&repo=johnmartel/.github)](https://dependabot.com)


This repository defines basic, shareable settings for repositories owned by this organization.


## Usage

Files defined in [.github](.github/) (excluding [settings.yml](.github/settings.yml)) contain configurations that can be
extended by other repositories in this organization. For more details, see [probot-config/recipes](https://github.com/probot/probot-config#recipes). 


## Contributing

### Validation

To validate settings, simply run `npm run lint`.

### Github workflows

To validate Github workflows before pushing a PR, simply run `npm run lint:workflows`.
