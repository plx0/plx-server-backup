# PLX Server Backup — public information

Static application home page and privacy policy for a personal rclone workflow that backs up selected files from an Oracle-hosted server to the owner's Google Drive using the intended `drive.file` scope.

- Home: https://plx0.github.io/plx-server-backup/
- Privacy: https://plx0.github.io/plx-server-backup/privacy.html

Publish with GitHub Pages from the root of `main`. No build step or third-party assets are required.

This repository is for public documentation only. Do not upload rclone configurations, OAuth credentials or tokens, service-account files, environment files, logs, or backup data. The ignore file uses an explicit allowlist; it does not protect files uploaded through GitHub's web interface or files explicitly forced into Git.

The privacy policy describes the intended personal configuration; the server, encryption settings, logs, actual OAuth requests, and retention configuration have not been audited as part of this website. The operator must keep runtime behavior consistent with the published policy.

## Google Auth Platform

Application home page and privacy policy URLs are above. The candidate authorized domain is `plx0.github.io` (no scheme or path), subject to Google's validation. Accepting a domain in that field does not verify its ownership. Do not register the shared `github.io` domain as if you own it.

Google's brand/domain verification requirements must be checked separately. A Search Console URL-prefix verification is not necessarily sufficient for OAuth domain verification. If Google requires DNS-level Domain Property verification, use a domain you control and map it to GitHub Pages, verify it using the project's owner account, and update both URLs. Personal-use verification exceptions and the Audience publishing state are distinct from verified branding.
