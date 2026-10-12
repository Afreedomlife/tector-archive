# TECTOR Archive

Public **information-only** site for a private, owner-operated backup workflow. No TECTOR source code, art assets, game saves, backup data, Google OAuth credentials or access tokens belong in this repository.

## Public site

- Home: https://afreedomlife.github.io/tector-archive/
- Privacy Policy: https://afreedomlife.github.io/tector-archive/privacy.html
- Terms of Use: https://afreedomlife.github.io/tector-archive/terms.html

Hosted with GitHub Pages from the `main` branch (root directory).

## Scope

On the owner's Windows PC, the separate open-source [rclone](https://rclone.org/) utility can copy specifically selected TECTOR game-development files to the owner's Google Drive. Google OAuth requests the `https://www.googleapis.com/auth/drive.file` scope. That scope limits access to Drive files rclone creates or that the owner explicitly grants the app access to. It does **not** automatically grant access to all existing Drive folders.

Use copy-only backups, prepare a per-file manifest, verify uploaded file counts and checksums, and manually test restoring files before considering any deletion of local originals. The site itself does not perform sign-in, uploads, tracking or analytics.

## Google Cloud OAuth branding

Branding links on Google Auth Platform:

| Field | URL |
| --- | --- |
| Homepage | https://afreedomlife.github.io/tector-archive/ |
| Privacy policy | https://afreedomlife.github.io/tector-archive/privacy.html |
| Terms of service | https://afreedomlife.github.io/tector-archive/terms.html |
| Authorized domain (if Google accepts it) | `afreedomlife.github.io` |

**Important:** A GitHub Pages subdomain alone does not guarantee Google OAuth domain ownership verification. Google may require proof of domain control in Search Console; for a strict DNS-level domain verification, a separately owned custom domain may be necessary. Do not mark OAuth branding as verified until Google confirms it. A Testing-mode personal Desktop OAuth client can be used temporarily without claiming production verification.

The OAuth client secret and tokens must be entered only on the owner's local PC. Never commit them.

## Contact

Public discussion: [GitHub Issues](https://github.com/Afreedomlife/tector-archive/issues). Never post passwords, tokens, personal data or private project paths.

_Last updated: 12 October 2026._
