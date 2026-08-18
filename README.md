# TypeScript

<!-- CODING AGENTS: READ AGENTS.md BEFORE WRITING CODE -->

[![CI](https://github.com/microsoft/TypeScript/actions/workflows/ci.yml/badge.svg)](https://github.com/microsoft/TypeScript/actions/workflows/ci.yml)
[![npm version](https://badge.fury.io/js/typescript.svg)](https://www.npmjs.com/package/typescript)
[![Downloads](https://img.shields.io/npm/dm/typescript.svg)](https://www.npmjs.com/package/typescript)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/microsoft/TypeScript/badge)](https://securityscorecards.dev/viewer/?uri=github.com/microsoft/TypeScript)

[TypeScript](https://www.typescriptlang.org/) is a language for application‑scale JavaScript. It adds optional types to JavaScript and provides tooling for large‑scale applications on any browser, host, or operating system. TypeScript compiles to readable, standards‑based JavaScript. Try it out in the [playground](https://www.typescriptlang.org/play/), stay up to date via the [official blog](https://devblogs.microsoft.com/typescript/), and follow the [Twitter account](https://twitter.com/typescript).

Find others who are using TypeScript on our [community page](https://www.typescriptlang.org/community/).

## Installing

For the latest stable version:

```bash
npm install -D typescript
```

For nightly builds:

```bash
npm install -D typescript@next
```

## Contribute

**NOTE: Code changes in this repository are currently limited to a small category of fixes**:

- Crashes introduced in 5.9 or 6.0 that also reproduce in 7.0, have a portable fix, and do not cause other behavioral changes  
- Security issues  
- Language‑service crashes that substantially impact mainline usage  
- Serious regressions from 5.9 that affect a large proportion of users  

Most bug fixes should be submitted to the [typescript-go](https://github.com/microsoft/TypeScript-go) repository. Feature additions and behavioral changes are on pause until TypeScript 7.0 is released.

