# @bussin/utilities

[![NPM Version](https://img.shields.io/npm/v/@bussin/utilities)](https://npmjs.com/package/@bussin/utilities) [![NPM Version](https://img.shields.io/npm/dw/@bussin/utilities)](https://npmjs.com/package/@bussin/utilities) [![NPM Version](https://img.shields.io/bundlephobia/min/@bussin/utilities)](https://npmjs.com/package/@bussin/utilities)

Core TypeScript utilities, types, models, and error-classes shared across all @bussin modules.

License: [MIT](https://opensource.org/licenses/MIT)

## Installation

```bash
    npm install @bussin/utilities
```

## Quick Start

```TypeScript
import { generateUUID } from '@bussin/utilities/uuid';
import { JsonObject } from '@bussin/utilities/types';

const obj: JsonObject = {
    id: generateUUID(),
};

```

## Publishing

Package releases are handled through GitHub Actions. In the Github repository, navigate to "Actions" -> "[Manual Release Dispatcher](https://github.com/wesleythorsen1/utilities/actions/workflows/release-dispatch.yml)" -> "Run workflow". Select the source branch and enter the new package version, then click the "Run workflow" button to start the release.

Alternatively, you can use the following to start the "Manual Release Dispatcher" workflow from the current branch via the CLI:

```bash
npm run release -- version=1.2.3
```

Package releases require a manual approval step. Once the workflow's build and tests complete, a new GitHub Release draft will be created that contains a link to approve the final stage of the release workflow.

Approving the final stage of the "Release & Publish" workflow will publish the package to NPM and publish the draft GitHub Release.

## Support

Please create a PR if you find any missing functionality that you's like to add. For bugs, please use the [issues tracker](https://github.com/wesleythorsen1/utilities/issues). I'd be happy to help you!
