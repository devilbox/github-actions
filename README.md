# GitHub Action Reusable Workflows

[![Tag](https://img.shields.io/github/tag/devilbox/github-actions.svg)](https://github.com/devilbox/github-actions/releases)
[![License](https://img.shields.io/badge/license-MIT-%233DA639.svg)](https://opensource.org/licenses/MIT)

Required GitHub Action Reusable Workflows for Devilbox. See [.github/workflows](.github/workflows).


## :computer: Usage

See how the reusable workflows are used [from this repository](https://github.com/devilbox/github-actions/network/dependents).


## :exclamation: Keep up-to-date with GitHub Dependabot


| :warning: UPDATE    |
|:--------------------|
| The following is not yet available as part of Dependabots package ecosystem.<br/>https://github.community/t/dependabot-with-reusable-workflow-versions/207372/4 |


Since [Dependabot](https://docs.github.com/en/github/administering-a-repository/keeping-your-actions-up-to-date-with-github-dependabot) has [native GitHub Actions support](https://docs.github.com/en/github/administering-a-repository/configuration-options-for-dependency-updates#package-ecosystem), to enable it on your GitHub repo all you need to do is add the `.github/dependabot.yml` file:

```yml
version: 2
updates:
  # Maintain dependencies for GitHub Actions
  - package-ecosystem: "github-actions"
    directory: "/"
    schedule:
      interval: "daily"
```

Then Dependabot will PR you version updates as soon as this repository gets updated.


## :page_facing_up: License

**[MIT License](LICENSE)**

Copyright (c) 2022 [cytopia](https://github.com/cytopia)
