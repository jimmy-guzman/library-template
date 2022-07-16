![actions][actions-badge]
[![version][version-badge]][package] [![downloads][downloads-badge]][npmtrends]
[![Code Coverage][coverage-badge]][coverage]
[![semantic-release][semantic-release-badge]][semantic-release]
[![code style: prettier][prettier-badge]][prettier]

# your-package-name

<!-- ![description starts here] -->

## Features

- [pnpm][pnpm] for fast and consistent installs
- [esbuild][esbuild] for fast builds powered by [tsup][tsup]
- [vitest][vitest] for fast unit tests
- [eslint][eslint] for static analysis
- [prettier][prettier] for formatting
- [commitlint][commitlint] to help enforce conventions
- [semantic-release][semantic-release] configuration
- [GitHub Actions][github-actions] with
  - install deps `pnpm` with cache
  - coverage reporting with [codecov][codecov]
  - lint commits on pull requests with [commitlint-action][commitlint-action]
  - spellcheck on pull requests with [cspell-action][cspell-action]

<!-- ![description ends here] -->

<!-- ![usage starts here] -->

## Usage

- [Use this template][use-template]

### Prerequisites

- [create secrets][create-secrets] for your new repo started from this template
  - `SEMANTIC_RELEASE`
  - `NPM_TOKEN`
- [create codecov account and token][codecov-quickstart]

### Steps

1. `./scripts/change-pkg-name.sh`
1. `./scripts/change-repo-name.sh`
1. `rm -rf scripts`

<!-- ![usage ends here] -->

<!-- badges links -->

[actions-badge]: https://img.shields.io/github/workflow/status/your-repo-user/your-repo-name/cicd?label=actions&logo=github-actions&style=flat-square
[version-badge]: https://img.shields.io/npm/v/your-package-name.svg?logo=npm&style=flat-square
[package]: https://www.npmjs.com/package/your-package-name
[downloads-badge]: https://img.shields.io/npm/dm/your-package-name.svg?logo=npm&style=flat-square
[npmtrends]: http://www.npmtrends.com/your-package-name
[semantic-release]: https://semantic-release.gitbook.io/semantic-release/
[semantic-release-badge]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square
[coverage-badge]: https://img.shields.io/codecov/c/github/your-repo-user/your-repo-name.svg?style=flat-square
[coverage]: https://codecov.io/github/your-repo-user/your-repo-name
[prettier-badge]: https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square
[prettier]: https://github.com/prettier/prettier

<!-- features links -->

[pnpm]: https://pnpm.io
[esbuild]: https://esbuild.github.io
[tsup]: https://tsup.egoist.sh
[commitlint]: https://commitlint.js.org/#
[eslint]: https://eslint.org
[vitest]: https://vitest.dev
[codecov]: https://codecov.io
[github-actions]: https://github.com/features/actions
[cspell-action]: https://github.com/streetsidesoftware/cspell-action
[commitlint-action]: https://github.com/wagoid/commitlint-github-action

<!-- usage links -->

[use-template]: https://github.com/jimmy-guzman/library-template/generate
[create-secrets]: https://docs.github.com/en/actions/reference/encrypted-secrets#creating-encrypted-secrets-for-a-repository
[codecov-quickstart]: https://docs.codecov.io/docs/quick-start
