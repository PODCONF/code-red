![Big Bitcoin® — CODE RED](./Group%201253.png)
# CODE RED

**Big Bitcoin® — Notice of Color Transition**

**Effective January 3, 2027**

> This is a notice, not a proposal.

This repository contains the cryptographically signed CODE RED notice and the materials required to independently verify it.

## Files

- [CODE RED Notice](2027-01-03-code-red.txt)
- [Detached PGP Signature](2027-01-03-code-red.txt.sig)
- [Big Bitcoin® Public PGP Key](big-bitcoin-leadership-public.asc)
- [OpenTimestamps Proof](2027-01-03-code-red.txt.ots)

## Signing Identity

Big Bitcoin®  
podconf@podconf.xyz

**OpenPGP fingerprint:**

```text
AFC2 8CC4 7FC4 AAA7 25C3 647B 4B02 4301 3061 112A
```

The public key is also available at:

https://podconf.xyz/pgp/

## Verify the Signature

Download all three files into the same directory.

Import the public key:

```bash
gpg --import big-bitcoin-leadership-public.asc
```

Verify the notice:

```bash
gpg --verify 2027-01-03-code-red.txt.sig 2027-01-03-code-red.txt
```

A successful verification will report a good signature from Big Bitcoin®.

Verify the key fingerprint independently against the fingerprint published above and on our website.

## Document Integrity

SHA-256:

```text
5342502e944281170b9a709c0dd8c00f220a56be67d1d708a2ee2cc5fdc828b4
```

## Protocol Status

The notice does not modify the Bitcoin protocol, monetary policy, or consensus rules.

Additional Bitcoin timestamp and on-chain records will be linked here as they become available.

---

**Big Bitcoin®**

*In control.*
