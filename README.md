# Product Partner React SDK

A React SDK for interacting with the Product Partner API.

## Installation

```bash
npm install pp-react-sdk
```

or

```bash
yarn add pp-react-sdk
```

## Usage

```typescript
import { PPClient, Configuration } from 'pp-react-sdk';

// Initialize the client
const config = new Configuration({
  basePath: 'https://api.productpartner.ai',
  apiKey: 'YOUR_API_KEY'
});

const client = new PPClient(config);

// Use the client
const response = await client.someEndpoint();
```

## Development

This SDK is automatically generated from the Product Partner OpenAPI specification.

To build the SDK:

```bash
npm run build
```

## License

MIT
