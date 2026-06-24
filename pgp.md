---
layout: default
---

## PGP keys

Public keys for verifying my signatures and sending me encrypted mail.
**Confirm the full fingerprint out of band before trusting a key.**

### gg@condado.dev - personal

```
802A 939D ECC1 86E1 FD52  20CC 5FBF D625 E01E F53F
```

- **Download:** [gg.asc](https://openpgpkey.condado.dev/keys/gg.asc)
- **Auto-fetch:** `gpg --locate-keys gg@condado.dev` (via [WKD](https://wiki.gnupg.org/WKD))

### geyslan.gregorio@aquasec.com - work (OSS signing)

```
ECFE CDE1 C10E 8DB2 DACF  8E86 D2E9 8A1A 63DB DDAB
```

- **Download + import:** [geyslan.gregorio.asc](https://openpgpkey.condado.dev/keys/aquasec.com/geyslan.gregorio.asc), then `gpg --import geyslan.gregorio.asc`
- **Fetch from keyserver:** `gpg --keyserver keyserver.ubuntu.com --recv-keys ECFECDE1C10E8DB2DACF8E86D2E98A1A63DBDDAB`

`aquasec.com` has no WKD, so this key lives in my key repo and on the keyserver instead.

---

[Home](./){: style="text-align: center;"}
