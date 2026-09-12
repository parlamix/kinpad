# KinPad support

Only the latest official KinPad release receives support and security fixes unless its release notes say otherwise.

## Get help

- Use [Issues](https://github.com/parlamix/kinpad/issues/new/choose) for reproducible bugs.
- Use [Discussions](https://github.com/parlamix/kinpad/discussions) for questions, ideas, and product direction.
- Email [hello@kinpad.org](mailto:hello@kinpad.org) when a public post is not appropriate and the matter is not a security vulnerability.

For a suspected vulnerability, follow [SECURITY.md](SECURITY.md).

## A useful bug report

Include:

- the KinPad version;
- the Windows version;
- short steps to reproduce the problem;
- what you expected and what happened; and
- a small, sanitized log or screenshot when it helps.

Do not include document text, recovery files, credentials, private keys, tokens, private paths, or unredacted screenshots.

## Files and recovery

Saved documents remain ordinary `.txt` or `.md` files in the location you choose.

KinPad keeps local recovery data for unsaved work. A recovery backup creates an extra copy in a folder you choose. That copy is user-managed.

If KinPad offers recovered work, review it and save anything you want to keep as an ordinary file.

## Installation

KinPad works offline after installation. The installer may need internet to add Microsoft WebView2.

Use the EXE for a normal installation. The MSI is intended for organizational deployment. Download both only from the [official download page](https://kinpad.org/download/).

If installation fails, restart Windows once, download a fresh installer, and try again. Include the exact error in a support request if the problem continues.
