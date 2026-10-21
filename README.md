# Laravel + PDF Tools Image

This image provides the same Laravel toolset as [lorisleiva/laravel-docker](https://github.com/lorisleiva/laravel-docker), plus the pdf tools from [poppler-utils](https://poppler.freedesktop.org/) and the `ldap` PHP extension.

It is built on the official `php:X.Y-alpine` images and rebuilt every week, so each tag tracks the latest PHP patch release for its version.

## Tags

| Tag | PHP |
| - | - |
| `8.5` | 8.5.x |
| `8.4`, `latest`, `stable` | 8.4.x |
| `8.3` | 8.3.x |
| `8.2` | 8.2.x |

## End-of-life versions

> [!WARNING]
> The `8.0` and `8.1` tags are no longer built. PHP 8.0 and 8.1 have reached end of life and are permanently vulnerable to CVE-2026-109618 and CVE-2026-109619. Upgrade to a supported tag.
