# Taiper — decision support

Introduce Taiper at taiper.org: a decision-support direction consolidating the former TPAR and Semantic Language work. This is a presentation site, not an operational decision application. Illustration/studio content is retired.

## What you can do

- Maintain reviewed overview and getting-started content.
- Validate Japanese/English content and preview the configured site.

## Current scope

Product capabilities must be supported by reviewed source or approved service information; the name alone establishes no feature. The declared `@nuxtjp/localized-site` dependency is obtained from the official npm registry using the frozen lockfile. No deployment is performed by these instructions.

## Getting started

Install the public-registry dependencies declared in this repository. Dependabot proposes manifest and lockfile updates through independently verified pull requests.

Use `pnpm@10.29.3` and the Node.js version declared in `engines` in `package.json`. Run from this repository:

```sh
pnpm install --frozen-lockfile
pnpm validate:content
pnpm typecheck
pnpm test
pnpm build
```

## Documentation and source

[Usage guide](docs/getting-started.md)

[Verification cases](test) · [Contributing](CONTRIBUTING.md) · [Security reporting](SECURITY.md) · [License](LICENSE) · [Attribution notices](NOTICE)

[OSS responsibility and source completion](docs/oss-source-contract.md) defines the supported package boundary and required acceptance. It does not declare unexecuted source, distribution or production checks complete.

Dependency updates: [repository policy](docs/dependency-updates.md).
