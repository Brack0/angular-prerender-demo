# Angular Prerender Demo

## How to test prerender

1. Get latest version of Tour of heroes (Angular tutorial). Example : https://angular.io/generated/zips/toh-pt6/toh-pt6.zip
2. Install packages (NPM or Yarn, NPM is used here)
3. Add Angular Universal via `npx ng add @nguniversal/express-engine`
4. Optional : Fix browserslist issue with `safari 15.2-15.3` (using `npm audit fix` worked for me)
5. Generate static assets via `npm run prerender`
