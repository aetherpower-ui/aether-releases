# Aether Project releases

Official downloads, source archives and verification files for Aether and Nexus.

**Current system: Aether 0.5 RC11.** The release-candidate ISO images and current Aether Apps downloads are free. Paid licence sales and online credit purchases have not opened.

## Choose a product

| Product | Current release | Downloads |
| --- | --- | --- |
| Aether Next / Gaming | 0.5 RC11 | [ISO images and optional Setup](https://aether-project.net/en/download) |
| Aether Setup | 0.4 | [Windows EXE and Linux RUN](https://github.com/aetherpower-ui/aether-releases/releases/tag/aether-direct-0.4) |
| Nexus for Windows / Linux | 1.0.0-rc.11 | [Installer, portable, Linux packages and sources](https://github.com/aetherpower-ui/aether-releases/releases/tag/v1.0.0-rc.11) |
| Nexus for Android | 1.0.0-rc.10 | [Android test APK](https://github.com/aetherpower-ui/aether-releases/releases/tag/v1.0.0-rc.10) |
| Aether Apps | 0.3.0 | [Windows/Linux bundles, sources and signed checksums](https://github.com/aetherpower-ui/aether-releases/releases/tag/aether-apps-0.3.0) |

Nexus on iPhone and iPad uses the paired computer's web interface in Safari. There is no native iOS package in these releases.

This repository holds several products with independent version numbers. Use the table above rather than assuming that a single “Latest” label applies to every product. Older individual app installers remain in historical releases; the current Apps bundle is 0.3.0.

## Why is Setup still 0.4?

Setup is the optional download and USB-preparation assistant, not the operating system. The released Setup 0.4 reads the current catalogue at `https://aether-project.net/config.json`; the current system catalogue contains Aether 0.5 RC11. It also accepts a saved installation manifest.

The original ISO filenames contain `development` and are recorded in the signed checksum list. The public release label is **0.5 RC11**, a Release Candidate. Keeping the original names lets the downloaded files match that list.

## Download and verify

1. Choose an edition or application from the table.
2. Compare the downloaded file's SHA-256 with the corresponding release metadata.
3. For ISO and Apps releases, verify the signed checksum list using the published release key. Follow the [Windows/Linux verification guide](https://aether-project.net/en/security#verify).
4. For the operating system, follow the [USB installation guide](https://aether-project.net/en/installation). Downloading a file does not install the system.

Published release-key fingerprint:

```text
5822 6ABB 3EFB 10F3 FC27 5946 C576 1CFF 31D5 068C
```

ISO images are delivered through the Aether Cloudflare download service linked from the official website. Nexus RC11 includes `SHA256SUMS.txt` and release metadata. Windows installers currently do not have an Authenticode publisher certificate.

## Source archives and licences

The main branch is a release catalogue, not a combined development checkout. Versioned source archives are attached to the corresponding releases:

- [Aether Apps 0.3.0 sources](https://github.com/aetherpower-ui/aether-releases/releases/download/aether-apps-0.3.0/Aether-Apps-0.3.0-Sources.zip)
- [Nexus RC11 sources](https://github.com/aetherpower-ui/aether-releases/releases/download/v1.0.0-rc.11/Nexus-1.0.0-rc.11-Source.zip)
- [Project source index and upstream package sources](https://aether-project.net/en/project#source)

Different releases and components have different terms. Read [LICENSE.md](LICENSE.md) and the notices included in the downloaded package. Public availability of an archive does not give every component the same licence.

## Test scope and support

Read the [release checks and hardware estimates](https://aether-project.net/en/releases#zgodnosc). VM boot and package-launch checks are documented separately from physical phone, GPU and cross-network acceptance tests.

Use [Issues](https://github.com/aetherpower-ui/aether-releases/issues) for reproducible problems, or the [project contact page](https://aether-project.net/en/help). Include the product version, operating system and steps to reproduce. Do not post passwords, API keys, activation codes, private invitations or personal conversations.

Po polsku: [pobieranie](https://aether-project.net/pl/pobierz) · [wydania i wymagania](https://aether-project.net/pl/wydania) · [pomoc](https://aether-project.net/pl/pomoc).
