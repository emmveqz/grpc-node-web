# gRPC on Node.js

### Node.js Client and Server

Directory: [`packages/grpc-js`](./packages/grpc-js)

npm package: [@emmveqz/grpc-node-web](https://www.npmjs.com/package/@emmveqz/grpc-node-web)

### CORS

```typescript
import * as grpc from '@emmveqz/grpc-node-web'

const grpcServer = new grpc.Server({
  allowedOrigin: 'https://my-web-browser-app.com',
})
```

### @grpc/grpc-js

For a complete documentation, see github repo: [`grpc/grpc-node`](https://github.com/grpc/grpc-node/tree/master/README.md)
