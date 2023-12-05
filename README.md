# npm-cli-error-case
Test case for https://github.com/npm/cli/pull/6997

Running `npm install` from the root of this repo causes the following error to occur:

```
npm ERR! Cannot read properties of undefined (reading 'extraneous')

npm ERR! A complete log of this run can be found in: /Users/smalton/.npm/_logs/2023-12-05T15_15_53_859Z-debug-0.log
```
