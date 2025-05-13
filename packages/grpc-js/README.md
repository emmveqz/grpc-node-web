# Fork to [@grpc/grpc-js](https://www.npmjs.com/package/@grpc/grpc-js) with CORS capability

## Installation

Node 12 is recommended. The exact set of compatible Node versions can be found in the `engines` field of the `package.json` file.

```sh
npm install @emmveqz/grpc-node-web
```

## CORS

```typescript
import * as grpc from '@emmveqz/grpc-node-web'

const grpcServer = new grpc.Server({
  allowedOrigin: 'https://my-web-browser-app.com',
})
```

## @grpc/grpc-js

For a complete documentation, see github repo: [`grpc/grpc-node`](https://github.com/grpc/grpc-node/tree/master/packages/grpc-js/README.md)
