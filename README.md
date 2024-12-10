# Larasonic Documentation

Official documentation for Larasonic, available at [docs.larasonic.com](https://docs.larasonic.com).

This repository contains the documentation for Larasonic, built with Mintlify. The documentation covers:

- Installation guides
- Feature documentation
- API references
- Development guides
- Deployment instructions

### Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview documentation changes:

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` to re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
