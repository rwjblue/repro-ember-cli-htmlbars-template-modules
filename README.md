# repro-ember-cli-htmlbars-template-modules

This is a reproduction to showcase, templates are not re-exported as modules.

Setup:

```bash
yarn
ember s
```

Open the app in the browser, check the console tab, it has the following error
message:

```bash
Could not find module `repro-ember-cli-htmlbars-template-modules/components/foo/template` imported from `dummy/templates/components/foo`
```

I tried two versions of `ember-cli-htmlbars`:

- `3.1.0` -> works
- `4.0.5` -> does not work

With the same code given here.
