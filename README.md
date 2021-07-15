# jest-environment-linkedom

After migrating to ts for a project, my tests in jsdom started to get really slow.
So this is a todo project to try and get [LinkeDOM](https://github.com/WebReflection/linkedom) working in combination with testing-library/react.

## notes

This was forked from [jest-environment-jsdom-sixteen](https://github.com/SimenB/jest-environment-jsdom-sixteen) to try and see if simple modifications will suffice. 

## notes from fork
to install:

```bash
  npm install --save-dev jest-environment-jsdom-sixteen
```

or

```bash
  yarn add jest-environment-jsdom-sixteen --dev
```

with jest config:

```json
{
  "testEnvironment": "jest-environment-jsdom-sixteen"
}
```
