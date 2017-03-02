Steps:

Create package.json with dependencies
Run this to set offline cache: yarn config set yarn-offline-mirror ./npm-packages-offline-cache
This will create a .yarnrc file in your HOME directory. Let’s move this file to the project root.
Finally run: yarn install


ref: https://yarnpkg.com/blog/2016/11/24/offline-mirror/