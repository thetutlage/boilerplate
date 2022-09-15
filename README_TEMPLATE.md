<%= PACKAGE_NAME %>
> <%= PACKAGE_DESCRIPTION %>

<br />

<div align="center">

[![gh-workflow-image]][gh-workflow-url] [![npm-image]][npm-url] ![][typescript-image] [![license-image]][license-url] [![snyk-image]][snyk-url]

</div>

[gh-workflow-image]: https://img.shields.io/github/workflow/status/<%= REPO_HANDLE %>/test?style=for-the-badge
[gh-workflow-url]: https://github.com/<%= REPO_HANDLE %>/actions/workflows/test.yml "Github action"

[npm-image]: https://img.shields.io/npm/v/<%= PACKAGE_NAME %>/latest.svg?style=for-the-badge&logo=npm
[npm-url]: https://www.npmjs.com/package/<%= PACKAGE_NAME %>/v/latest "npm"

[typescript-image]: https://img.shields.io/badge/Typescript-294E80.svg?style=for-the-badge&logo=typescript

[license-url]: LICENSE.md
[license-image]: https://img.shields.io/github/license/<%= REPO_HANDLE %>?style=for-the-badge

[snyk-image]: https://img.shields.io/snyk/vulnerabilities/github/<%= REPO_HANDLE %>?label=Snyk%20Vulnerabilities&style=for-the-badge
[snyk-url]: https://snyk.io/test/github/<%= REPO_HANDLE %>?targetFile=package.json "snyk"
