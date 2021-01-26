# TemplateTypeScript

```
$ node -v
v15.6.0

$ npm -v
7.4.0

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

## recommended packages

- Date
	- [Moment.js]()
	- [Day.js]()
	- [Luxon]()
    - [date-fns](https://date-fns.org/)
        - Modern JavaScript date utility library
- [fast-csv](https://www.c2fo.io/fast-csv/)
    - CSV Parser and Formatter
- [fs-extra]()
- [nanoid](https://github.com/ai/nanoid/)
    - instead of `shortid`
- [graphdoc](https://github.com/2fd/graphdoc)
    - Static page generator for documenting GraphQL Schema
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