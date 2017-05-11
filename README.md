# elix-rollup-boilerplate
Boilerplate web project demonstrating use of Elix and Rollup. This project
uses Rollup to build a single build/bundle.js file.

## Getting started
* `npm install -g yarn`
* `yarn install`
 
## Building the project
* `yarn run build`

## Using a different branch of Elix
To build and run with a different branch of Elix, rather than the
package.json default of `elix/elix#master`, do the following:
1. `yarn remove elix`
2. `yarn add elix/#branch-name`

If you're finding that yarn is not getting the right branch, try:
1. `yarn remove elix`
2. `rm -rf node_modules`
3. `yarn cache clean`
4. `yarn install`
5. `yarn add elix/#branch-name`

In both cases, follow this with `yarn run build`