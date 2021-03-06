# Helix Version Picker

> A preflight service that determines if a repo has opted in to running an upcoming version of helix-pages.

## Status
[![codecov](https://img.shields.io/codecov/c/github/adobe/helix-version-picker.svg)](https://codecov.io/gh/adobe/helix-version-picker)
[![CircleCI](https://img.shields.io/circleci/project/github/adobe/helix-version-picker.svg)](https://circleci.com/gh/adobe/helix-version-picker)
[![GitHub license](https://img.shields.io/github/license/adobe/helix-version-picker.svg)](https://github.com/adobe/helix-version-picker/blob/main/LICENSE.txt)
[![GitHub issues](https://img.shields.io/github/issues/adobe/helix-version-picker.svg)](https://github.com/adobe/helix-version-picker/issues)
[![LGTM Code Quality Grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/adobe/helix-version-picker.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/adobe/helix-version-picker)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

## Installation

## Usage

```bash
curl https://adobeioruntime.net/api/v1/web/helix/helix-services/version-picker@v1
```

For more, see the [API documentation](docs/API.md).

## Development

### Deploying Helix Version Picker

Deploying Helix Version Picker requires the `wsk` command line client, authenticated to a namespace of your choice. For Project Helix, we use the `helix` namespace.

All commits to `main` that pass the testing will be deployed automatically. All commits to branches that will pass the testing will get commited as `/helix-services/version-picker@ci<num>` and tagged with the CI build number.
