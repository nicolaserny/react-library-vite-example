# Create a React Library with TypeScript and Vite

This repository is an example of a React library created with TypeScript and Vite.

## Getting Started

First, install the dependencies of the monorepo:

```bash
yarn install
```

Build the library:

```bash
cd packages/my-lib && yarn build
```

Run the development server of the test project:

```bash
cd sites/my-site && yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

If you want to start the storybook server, run:

```bash
cd packages/my-lib && yarn storybook
```
