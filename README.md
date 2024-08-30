## MF Remote Entry Chunk Size Investigations

### Not Minified

Size of remoteEntry chunks: 196kB

To reproduce do either

1. `npx nx serve host` -> look at the network tab in browser
2. `nppx nx build remote1 --configuration=development` -> inspect file at `dist/apps/remote1/remoteEntry.js`

### Minified

Size of remoteEntry chunks: 75.4kB

To reproduce do either

1. `npx nx serve host --configuration=production` -> look at the network tab in browser
2. `nppx nx build remote1` -> inspect file at `dist/apps/remote1/remoteEntry.js`

