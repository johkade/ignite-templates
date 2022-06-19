# ignite-templates

ignite helps you generating files from your custom .ejs-templates.

included so far:

- [x] RN Component
- [x] RN Screen
- [ ] Zustand Store

#### setup and usage

- add the following to your package.json:

```js
"scripts": {
    // ...
    "comp": "npx ignite-cli g component",
    "screen": "npx ignite-cli g screen"
  },
```

- add the template folders of this repo to `root/ignite`
- run the following commands:

```sh
# create Button component in root/app/components/button
yarn comp Button

# create HomeScreen component/screen in root/app/screens
yarn screen Home
```

#### disclaimer

These templates are heavily opinionated, e.g.:

- the folder names (as of now, ignite doesn't allow custom output folders)
- the generated code (usage of react-navigation and so on)

LICENSE:
MIT
