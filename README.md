# React DOM Tests in a Real Browser

This repo uses Karma to launch **real instances of Chrome instead of using Jest+JSDOM**!

This setup allows you to run in Headful or Headless Chrome and visually debug your DOM tests, which is simply not possible in the default CRA+Jest+JSDOM setup.  

With this setup, you can still use React Testing Library as you may be used to - it just works! 💥

‼️ For a version that is compatible with both Jest+JSDOM and Karma+Chrome, check out this repo: https://github.com/smzelek/react-dom-tests-in-chrome .

### Run with Chrome in Karma
```bash
npm run test:realdom
# karma start --single-run
```
