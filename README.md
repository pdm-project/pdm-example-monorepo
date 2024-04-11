# PDM Monorepo Example

This is an example of a monorepo managed by [PDM](https://pdm.fming.dev).

## Sub Packages

- `packages/pkg-core`
- `packages/pkg-first`
- `packages/pkg-second`


## Note about `pdm instal


If you change the dependencies in one of the subprojects, the `pdm install` command will not detect that the lock file needs to be re-generated.

You will thus have to run `pdm lock` manually, before running `pdm install`. 
