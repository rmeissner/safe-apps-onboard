# Safe Apps Onboard

This is a wrapper around [Onboard](https://github.com/blocknative/onboard) that adds Safe Apps support.

If the app using the wrapper is run as a Safe App the `walletSelect` method will automatically connect to the Safe App.

### How to use

- Add dependency to `package.json` and run install

```
"safe-apps-onboard": "https://github.com/rmeissner/safe-apps-onboard#main",
```

- Setup Safe App
  - See https://docs.gnosis.io/safe/docs/sdks_safe_apps/


- Use `Onboard` from `safe-apps-onboard` instead from `bnc-onboard`

```js
import Onboard from 'safe-apps-onboard'

export const onboard = Onboard(onboardOptions)
```
