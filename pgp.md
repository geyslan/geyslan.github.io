---
layout: default
---

# PGP / OpenPGP keys

Public keys for verifying my signatures and for sending me encrypted mail.
**Always confirm the full fingerprint through a second channel before trusting a
key** — don't rely on the download alone.

## gg@condado.dev — personal

```
802A 939D ECC1 86E1 FD52  20CC 5FBF D625 E01E F53F
```

- **Download:** [armored key](https://openpgpkey.condado.dev/keys/gg.asc)
- **Auto-fetch ([WKD](https://wiki.gnupg.org/WKD)):**

  ```
  gpg --locate-external-keys gg@condado.dev
  ```

  `gpg` resolves and imports the key straight from `condado.dev` — no keyserver,
  no manual download.

## geyslan.gregorio@aquasec.com — work (OSS signing)

```
(fingerprint pending — key not yet published here)
```

- **Download:** _pending_
- WKD is not available for `aquasec.com` yet, so this key is download-only.

---

[Home](./){: style="text-align: center;"}
