# subpkg

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] subpkg`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree subpkg`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init subpkg
kpt live apply subpkg --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
