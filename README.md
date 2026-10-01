# Bazarr+ packages

Store files for Bazarr+ 2.7.0 (v2.7.0), prepared for https://github.com/LavX/bazarr-packages on branch `main`.
Nothing here is published until this tree is pushed to that repository, and no store lists Bazarr+
until that store accepts it.

The GitHub release and registry digests were verified when this tree was generated. Review and native install checks still decide publication.

## Install routes

| Ecosystem | Path in this tree | Package revision | How it is used |
| --- | --- | --- | --- |
| Runtipi | `apps/bazarr-plus/` | 1 | Add https://github.com/LavX/bazarr-packages as a custom app store, branch `main`. |
| CasaOS / ZimaOS | `Apps/BazarrPlus/`, `Apps/BazarrPlusStack/` | 1.0.0 | Build with the official v2 store tooling and publish the result. The store URL is then https://lavx.github.io/bazarr-packages |
| Unraid | `templates/bazarr-plus.xml`, `ca_profile.xml` | 1.0.0 | Template repository https://github.com/LavX/bazarr-packages. TemplateURL: https://raw.githubusercontent.com/LavX/bazarr-packages/main/templates/bazarr-plus.xml |
| Compose / Portainer | `stacks/bazarr-plus/` | 1.0.0 | Compose file: https://raw.githubusercontent.com/LavX/bazarr-packages/main/stacks/bazarr-plus/compose.yaml Media overlay example: https://raw.githubusercontent.com/LavX/bazarr-packages/main/stacks/bazarr-plus/compose.media.yaml.example |
| TrueNAS | `submissions/truenas/` | 1.0.0 | Copy `ix-dev/community/bazarr-plus` into a `truenas/apps` pull request. Catalog tooling generates `item.yaml`. |

## Pinned images

- `ghcr.io/lavx/bazarr:2.7.0@sha256:90a5c184b0af41602ff78ea7286e0c5f2c4c284c9b18f71427d9ddbeb0b6531c`
- `ghcr.io/lavx/ai-subtitle-translator:v2.1.1@sha256:e22abba9625b96df6727354f10933da312a084ffeae68f0eb1f9a82492f5e48d`
- `ghcr.io/flaresolverr/flaresolverr:v3.5.2@sha256:c80ae007ce2ccdcd217a12426e4f039ef763ff90738c808d38810c3e59323767`

Runtime profile: atlas-sidecar. Source commit `9f76ccc550c62a72f96bf4f6ba259dfd72837021` of
https://github.com/LavX/bazarr. [EXPORT.json](EXPORT.json) records the lock hash and the SHA-256 of every
file in this tree. See [LICENSE](LICENSE) and [NOTICES.md](NOTICES.md); the TrueNAS library keeps
[its own license](submissions/truenas/LICENSE.LGPL-3.0).
