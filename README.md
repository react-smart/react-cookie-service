# React Cookie Service

Simple library to manage cookies in React. Implementation is similar
to [Ngx Cookie Service](https://github.com/stevermeister/ngx-cookie-service)

[![NPM](https://img.shields.io/npm/v/@ngxsmart/react-cookie-service.svg)](https://www.npmjs.com/package/@ngxsmart/react-cookie-service)

## Install

```bash
npm install --save @ngxsmart/react-cookie-service
```

## Usage

```tsx
import React, { Component } from 'react'
import { useCookies } from '@ngxsmart/react-cookie-service';


export default function Example() {
  const { getCookies } = useCookies();
  return (
    <div>
      <h2>{JSON.stringify(getCookies)}</h2>
    </div>
  )
}
```

## Build

Use the following command to build the library

```bash
nx build react-cookie-service
```

## Publish to NPM

Use the following command to publish the library to NPM

```bash
npm publish dist/libs/react-cookie-service/
```

## License

MIT © [pavankjadda](https://github.com/pavankjadda)
