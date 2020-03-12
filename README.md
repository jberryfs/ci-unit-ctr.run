# CI Unit ctr.run

Provides expanded `Dockerfile` definitions for use with [ctr.run](http://ctr.run) since it does not currently support Docker build args.

## Usage

```
docker pull ctr.run/github.com/jberryfs/ci-unit-ctr.run/path/to/base/image
```

## Update

Make changes to `images.list` and run `./generate`. Commit and push the result.
