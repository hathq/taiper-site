# Using @creative/taiper-site

Present approved information introducing Taiper.

## Before you start

Product capabilities must be supported by reviewed source or approved service information; the name alone establishes no feature. The declared `@nuxtjp/localized-site@0.1.0` dependency is obtained from the official npm registry using the frozen lockfile. No deployment is performed by these instructions.

## First steps

Install the exact published dependency versions from the official npm registry using the frozen lockfile. No local package archives are required.

Run from the repository root:

```sh
pnpm install --frozen-lockfile
pnpm validate:content
pnpm typecheck
pnpm test
pnpm build
```

## How to assess the result

- Maintain reviewed overview and getting-started content.
- Validate Japanese/English content and preview the configured site.

A passing source-level check establishes only what that check observes. Keep missing configuration, unavailable services and unverified deployment paths visible.

## Continue reading

[Repository overview](../README.md)
