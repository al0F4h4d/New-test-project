# New Test Project

A Node.js starter project by Fahad. It uses CommonJS and loads environment variables with [dotenv](https://github.com/motdotla/dotenv).

## Requirements

- Node.js 12 or later
- npm

## Setup

```bash
npm install
```

Create a `.env` file in the project root for any secrets or config you do not want in source control:

```env
EXAMPLE_KEY=example_value
```

## Run

The package entry point is `index.js`. After you add that file:

```bash
node index.js
```

Load variables from `.env` at the top of your entry file:

```js
require("dotenv").config();
```

## Scripts

| Script | Description |
| --- | --- |
| `npm test` | Placeholder; no tests are defined yet |

## License

ISC
