# @bussin/utilities

[![NPM Version](https://img.shields.io/npm/v/@bussin/utilities)](https://npmjs.com/package/@bussin/utilities) [![NPM Version](https://img.shields.io/npm/dw/@bussin/utilities)](https://npmjs.com/package/@bussin/utilities) [![NPM Version](https://img.shields.io/bundlephobia/min/@bussin/utilities)](https://npmjs.com/package/@bussin/utilities)

Core TypeScript utilities, types, models, and error-classes shared across all @bussin modules.

License: [MIT](https://opensource.org/licenses/MIT)

## Installation

    npm install @bussin/utilities

## Quick Start

```TypeScript
import { generateUUID } from '@bussin/utilities/uuid';
import { JsonObject } from '@bussin/utilities/types';

const obj: JsonObject = {
    id: generateUUID(),
};

```

## Support

Please create a PR if you find any missing functionality that you's like to add. For bugs, please use the [issues tracker](https://github.com/wesleythorsen1/utilities/issues). I'd be happy to help you!
