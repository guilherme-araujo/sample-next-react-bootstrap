# Next.js with react-bootstrap example

This example shows how to use Next.js along with [react-bootstrap](https://react-bootstrap.github.io/).

## Deploy your own

Deploy the example using [Vercel](https://vercel.com):

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/vercel/next.js/tree/canary/examples/with-react-bootstrap)

## How to use

Execute [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app) with [npm](https://docs.npmjs.com/cli/init) or [Yarn](https://yarnpkg.com/lang/en/docs/cli/create/) to bootstrap the example:

```bash
npx create-next-app --example with-react-bootstrap with-react-bootstrap-app
# or
yarn create next-app --example with-react-bootstrap with-react-bootstrap-app
```

Deploy it to the cloud with [Vercel](https://vercel.com/import?filter=next.js&utm_source=github&utm_medium=readme&utm_campaign=next-example) ([Documentation](https://nextjs.org/docs/deployment)).

## Additional changes made by me (guilherme-araujo)

    yarn add typescript @types/react @types/node -D

Rename files .jsx to .tsx

    yarn add eslint -D
    yarn eslint --init (fix npm to yarn package manager)
    yarn add prettier eslint-plugin-prettier eslint-config-prettier -D

.eslintrc.json from https://github.com/rocketseat-content/react-nextjs-typescript-structure/blob/master/.eslintrc.json

.eslintignore contents

    node_modules
    .next
    /*.js

.prettier.config.js from https://github.com/rocketseat-content/react-nextjs-typescript-structure/blob/master/prettier.config.js

.editorconfig contents:

    root = true

    [*]
    indent_style = space
    indent_size = 2
    charset = utf-8
    end_of_line = lf
    trim_trailing_whitespace = true
    insert_final_newline = true

