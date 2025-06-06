# #discussion/36278

First, read the [Renovate minimal reproduction instructions](https://github.com/renovatebot/renovate/blob/main/docs/development/minimal-reproductions.md).

## Current behavior

Renovate does nothing even though the kotlinx-datetime lib used is outdated. Is 0.6.1 when the latest version (as time of writing) would be the 0.6.2.

See the renovate logs [here](https://developer.mend.io/github/janseeger/amper-minimal-reproduction-template/-/job/b092dbe2-a7a5-4fa1-8f66-e0b6108c73e5)

## Expected behavior

Renovate finds and reports the outdated library.

## Link to the Renovate issue or Discussion

[Add support for Amper standalone projects #36278](https://github.com/renovatebot/renovate/discussions/36278)
