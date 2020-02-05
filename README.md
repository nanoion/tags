 [![Test Status](https://github.com/gobuffalo/tags/v3/workflows/Tests/badge.svg)](https://github.com/gobuffalo/tags/v3/actions)
 [![Go Report Card](https://goreportcard.com/badge/github.com/gobuffalo/tags/v3)](https://goreportcard.com/report/github.com/gobuffalo/tags/v3)

# Tags

Easily build HTML tags in Go! This package is especially useful when using [http://gobuffalo.io](http://gobuffalo.io).

## Getting Started
### Prerequisites

Tags has a minimum Go dependency of 1.8.1.

### Installing

To get this lib just get it via `go get`

```
go get -u -v github.com/gobuffalo/tags/v3/...
```
## Running the tests

In order to run the tests just do it with a regular

```
go test ./...
```
## Documentation

Documentation is currently in [this repository Wiki](https://github.com/gobuffalo/tags/v3/wiki), you can find there instructions on how to use tags within your app.

## Contributing

If you want to contribute, please read this article first: [Contributing to Open Source Git Repositories in Go](https://splice.com/blog/contributing-open-source-git-repositories-go/). It shows how to configure your git environment to avoid common pitfalls. This article is recommended to all those who are looking to contribute to any Go projects.

^ Taken from [gobuffalo.io](https://https://gobuffalo.io/docs/contributing)

### ⚠️ Send PRs to development branch

The way we release in Tags is:

1. We use `development` branch to accumulate changes to be released 
2. Once we decide to make a release we send a PR from `development` to `master` with those changes to be added.
3. Once that PR gets merged we tag a new release with the vX.X.X scheme.