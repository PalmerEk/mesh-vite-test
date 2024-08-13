# Mesh - Vite + Nuxt 3

Test project to use Mesh SDK with Vite + Nuxt 3.

## Setup

Make sure to install the dependencies:

```bash
# npm
npm install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
# npm
npm run dev
```

## Cleanup

Remove the package-lock, node_modules, cache folders etc... (must run npm i after):

```bash
# npm
npm run clean
```

## Notes

Doesn't work (similar as installing from npm registry)
```
"@meshsdk/core": "file:../mesh/packages/mesh-core/dist/meshsdk-core-1.6.4.tgz",
```

Works
```
"@meshsdk/common": "file:../mesh/packages/mesh-common",
"@meshsdk/core": "file:../mesh/packages/mesh-core",
"@meshsdk/core-csl": "file:../mesh/packages/mesh-core-csl",
"@meshsdk/core-cst": "file:../mesh/packages/mesh-core-cst",
"@meshsdk/core-provider": "file:../mesh/packages/mesh-core-provider",
"@meshsdk/core-transaction": "file:../mesh/packages/mesh-core-transaction",
"@meshsdk/core-wallet": "file:../mesh/packages/mesh-core-wallet",
```