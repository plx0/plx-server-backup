# PLX Server Backup — public information

Static application home page and privacy policy for a personal rclone workflow that backs up selected files from an Oracle-hosted server to the owner's Google Drive using the intended `drive.file` scope.

- Home: https://plx-server-backup.duckdns.org/
- Privacy: https://plx-server-backup.duckdns.org/privacy.html

Publish with GitHub Pages from the root of `main`. No build step or third-party assets are required.

This repository is for public documentation only. Do not upload rclone configurations, OAuth credentials or tokens, service-account files, environment files, logs, or backup data. The ignore file uses an explicit allowlist; it does not protect files uploaded through GitHub's web interface or files explicitly forced into Git.

The privacy policy describes the intended personal configuration; the server, encryption settings, logs, actual OAuth requests, and retention configuration have not been audited as part of this website. The operator must keep runtime behavior consistent with the published policy.

## Google Auth Platform

Project: `plx-backups` (PLX-Backups). Intended scope: `https://www.googleapis.com/auth/drive.file`.

- Application home page: https://plx-server-backup.duckdns.org/
- Privacy policy: https://plx-server-backup.duckdns.org/privacy.html
- Authorized domain: `plx-server-backup.duckdns.org`

The free subdomain is managed through the owner's DuckDNS account. DNS-level ownership verification succeeded in Google Search Console on 22 October 2026 using the Google account associated with the Cloud project. Keep its public Google verification TXT record in DNS; no private DNS management token belongs in this repository.

The app's Audience publishing state is **In production**. This state is separate from verified branding. Google may require up to 24 hours after ownership verification before a new branding check recognizes it. HTTPS readiness and Google's branding acceptance must be confirmed independently; neither follows merely from creating a domain or adding it to Authorized domains.

DNS currently points to a GitHub Pages address. Do not run a dynamic IP updater for this domain: that would replace the website destination. If DNS or hosting changes, check the live HTTPS home and privacy URLs before changing OAuth branding.
