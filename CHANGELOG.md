# StencilSwiftKit CHANGELOG

---

## Master (to be 5.0.0)

### Bug Fixes

### New Features

### Internal Changes

* Add a "parameters parser" able to transform parameters passed as a set of strings (`a=1 b.x=2 b.y=3 c=4 c=5`) — typically provided as the command line arguments of a CLI — into a Dictionary suitable for Stencil contexts.  
  [#8](https://github.com/SwiftGen/StencilSwiftKit/pull/8)

## Before 5.0.0

This first version of `StencilSwiftKit` is numbered `5.0.0` because it's the result of splitting the parts of `SwiftGen` into separate frameworks during its `5.0.0` release. This way, all parts of SwiftGen will start up with matching versions.

`StencilSwiftKit` is the framework used by SwiftGen to extend the Stencil template engine with nodes and filters specialized in generating Swift code. It is used at least by both `SwiftGen` and `Sourcery`, as both tools use Stencil templates to generate Swift code.

_For the list of older `CHANGELOG` history, see SwiftGen's own `CHANGELOG` for changes listed before `5.0.0` and before SwiftGen was split in separate frameworks._
