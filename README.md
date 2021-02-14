# TemplateTypeScript

```
$ node -v
v15.6.0

$ npm -v
7.5.2

$ yarn -v
1.22.10

$ npx tsc --version
Version 4.1.3

$ ./node_modules/.bin/eslint --version
v7.18.0

$ ./node_modules/.bin/prettier --version
2.2.1
```

## setup

- `package.json`
    - name
	- description
	- GitHub URLs

## installed packages

- Development
    - ts-node
    - ts-node-dev
    - npm-run-all
    - rimraf
- Lint
    - ESLint
    - Prettier
- Commit
    - husky 
    - lint-staged

### not recommended packages

- eslint-loader
- shortid
    - shortid is deprecated, because the architecture is unsafe.
- aws-sdk(v2)
	- should use aws-sdk(v3)

## recommended packages

- Date
	- [Moment.js]()
	- [Day.js]()
	- [Luxon]()
    - [date-fns](https://date-fns.org/)
        - Modern JavaScript date utility library
- FileSystem
	- [fast-csv](https://www.c2fo.io/fast-csv/)
		- CSV Parser and Formatter
    - [fs-extra](https://github.com/jprichardson/node-fs-extra)
		- adds file system methods that aren't included in the native fs module and adds promise support to the fs methods.
- UI (CSS-in-JS, etc...)
    - [emotion](https://github.com/emotion-js/emotion)
        - Emotion is a performant and flexible CSS-in-JS library
    - [styled-components](https://github.com/styled-components/styled-components)
        - Visual primitives for the component age. Use the best bits of ES6 and CSS to style your apps without stress
    - [material-ui](https://github.com/mui-org/material-ui)
        - Material-UI is a simple and customizable component library to build faster, beautiful, and more accessible React applications
	- [quasar](https://github.com/quasarframework/quasar)
		- Quasar Framework - Build high-performance VueJS user interfaces in record time
- AWS
	- [AWS SDK for JavaScript v3](https://github.com/aws/aws-sdk-js-v3)
		- [Documents for Javascript v3](https://docs.aws.amazon.com/AWSJavaScriptSDK/v3/latest/)
- DI
	- [InversifyJS](https://github.com/inversify/InversifyJS)
		- A powerful and lightweight inversion of control container for JavaScript & Node.js apps powered by TypeScript.
- GraphQL
	- [apollo-client](https://github.com/apollographql/apollo-client)
		- 🚀 A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server
- not classified
	- [nanoid](https://github.com/ai/nanoid/)
		- instead of `shortid`
	- [graphdoc](https://github.com/2fd/graphdoc)
		- Static page generator for documenting GraphQL Schema
	- [pixela](https://github.com/a-know/Pixela)
		- Record and Track your habits or effort. All by API.
	- [redux](https://github.com/reduxjs/redux)
		- Redux is a predictable state container for JavaScript apps
		- [Redux 入門 〜Reduxの基礎を理解する〜](https://qiita.com/soarflat/items/bd319695d156654bbe86)

# commands

```shell
# runs once
$ npm run dev

# runs when file saved
$ npm run dev:watch

# build from TypeScript to JavaScript
$ npm run build

# run
$ npm run start
```

# References

- [TypeScript + Node.js プロジェクトのはじめかた](https://qiita.com/notakaos/items/3bbd2293e2ff286d9f49)
- [TypeScript + Node.jsプロジェクトにESLint + Prettierを導入する手順](https://qiita.com/notakaos/items/85fd2f5c549f247585b1)
- [tsconfig.jsonの全オプションを理解する](https://qiita.com/ryokkkke/items/390647a7c26933940470)