# parcel-example

Stating with `bsb -init parcel-example -theme react` we did the following

 - remove weback.config.js and webpack dev dependency
 - added parcel and npm-run-all to dev dependencies
 - changed index.html to point to `./index.re` instead of `../build/index.js`
 - updated npm scripts (note that we need to run bsb's watch compile and parcel concurrently)

Simply run `npm install` and `npm start` or `yarn` and `yarn start`