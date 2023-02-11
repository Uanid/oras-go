# ORAS Go library

![ORAS](https://github.com/oras-project/oras-www/raw/main/docs/assets/images/oras.png)

## Project status

### Versioning

The ORAS Go library follows [Semantic Versioning](https://semver.org/), where breaking changes are reserved for MAJOR releases, and MINOR and PATCH releases must be 100% backwards compatible.

### v2: stable

[![Build Status](https://github.com/oras-project/oras-go/actions/workflows/build.yml/badge.svg?event=push&branch=main)](https://github.com/oras-project/oras-go/actions/workflows/build.yml?query=workflow%3Abuild+event%3Apush+branch%3Amain)
[![codecov](https://codecov.io/gh/oras-project/oras-go/branch/main/graph/badge.svg)](https://codecov.io/gh/oras-project/oras-go)
[![Go Report Card](https://goreportcard.com/badge/oras.land/oras-go/v2)](https://goreportcard.com/report/oras.land/oras-go/v2)
[![Go Reference](https://pkg.go.dev/badge/oras.land/oras-go/v2.svg)](https://pkg.go.dev/oras.land/oras-go/v2)

The version `2` is actively developed in the [`main`](https://github.com/oras-project/oras-go/tree/main) branch with all new features.

Examples for common use cases can be found below:

- [Copy examples](https://pkg.go.dev/oras.land/oras-go/v2#pkg-examples)
- [Registry interaction examples](https://pkg.go.dev/oras.land/oras-go/v2/registry#pkg-examples)
- [Repository interaction examples](https://pkg.go.dev/oras.land/oras-go/v2/registry/remote#pkg-examples)
- [Authentication examples](https://pkg.go.dev/oras.land/oras-go/v2/registry/remote/auth#pkg-examples)

If you are seeking latest changes, you should use the [`main`](https://github.com/oras-project/oras-go/tree/main) branch (or a specific commit hash) over a tagged version when including the ORAS Go library in your project's `go.mod`.
The Go Reference for the `main` branch is available [here](https://pkg.go.dev/oras.land/oras-go/v2@main).

To migrate from `v1` to `v2`, see [MIGRATION_GUIDE.md](./MIGRATION_GUIDE.md).

### v1: stable

[![Build Status](https://github.com/oras-project/oras-go/actions/workflows/build.yml/badge.svg?event=push&branch=v1)](https://github.com/oras-project/oras-go/actions/workflows/build.yml?query=workflow%3Abuild+event%3Apush+branch%3Av1)
[![Go Report Card](https://goreportcard.com/badge/oras.land/oras-go)](https://goreportcard.com/report/oras.land/oras-go)
[![Go Reference](https://pkg.go.dev/badge/oras.land/oras-go.svg)](https://pkg.go.dev/oras.land/oras-go)

As there are various stable projects depending on the ORAS Go library `v1`, the
[`v1`](https://github.com/oras-project/oras-go/tree/v1) branch
is maintained for API stability, dependency updates, and security patches.
All `v1.*` releases are based upon this branch.

Since `v1` is in a maintenance state, you are highly encouraged
to use releases with major version `2` for new features.

## Docs

- [oras.land/client_libraries/go](https://oras.land/client_libraries/0_go/): Documentation for the ORAS Go library
- [Reviewing guide](https://github.com/oras-project/community/blob/main/REVIEWING.md): All reviewers must read the reviewing guide and agree to follow the project review guidelines.

## Code of Conduct

This project has adopted the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/master/code-of-conduct.md). See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for further details.
