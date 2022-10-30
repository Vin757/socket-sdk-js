# @socketsecurity/sdk

[![npm version](https://img.shields.io/npm/v/@socketsecurity/sdk.svg?style=flat)](https://www.npmjs.com/package/@socketsecurity/sdk)
[![TypeScript types](https://img.shields.io/npm/types/@socketsecurity/sdk.svg?style=flat)](https://www.npmjs.com/package/@socketsecurity/sdk)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](https://github.com/SocketDev/eslint-config)
[![Follow @SocketSecurity](https://img.shields.io/twitter/follow/SocketSecurity?style=social)](https://twitter.com/SocketSecurity)

SDK for the Socket API client, generated by `api`.

## Usage

```bash
npm install @socketsecurity/sdk
```

### ESM / TypeScript

```javascript
import { socketSdk } from '@socketsecurity/sdk'

const client = socketSdk.auth('yourApiKeyHere')

const res = await client.getIssuesByNPMPackage({
  package: '@socketsecurity/eslint-config',
  version: '1.0.0'
})
```

### CommonJS

```javascript
const { socketSdk } = require('@socketsecurity/sdk')
```

## See also

* [Socket API Reference](https://docs.socket.dev/reference)
* [Socket.dev](https://socket.dev/)
* [Socket GitHub App](https://github.com/apps/socket-security)
