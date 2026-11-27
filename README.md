**English** · [Español](README.es.md)

# expense me

**Your personal finances, private and free, on your Mac.** An app by
[Otherwise Technologies LLC](https://otherwisetech.com).

Receipts, accounts and statements, cards, loans, budget, upcoming bills, subscriptions, income and net
worth in one place, on your computer. No account, no subscription.

> **This repository only holds builds and documentation.** expense me is proprietary, closed-source
> software (free to use); its source code is not here. This is where you'll find the downloads, the
> notes for each version and the place to report problems.

## What it does

- **Home**: how much you can spend today without overspending, what's due soon and what deserves a look.
- **Receipts**: drag photos or PDFs onto the window; they're read on your computer and wait for you to
  review and save them.
- **Accounts and statements**: drop in your statements (password-protected PDFs, Excel, CSV) and they
  land in the right account, with their transactions and categories.
- **What I owe**, **My cards**, **My loans** and **Simulate a loan**: balances, rates, installments,
  statement and payment dates, a plan to get out of debt and loan offers side by side.
- **Income**, **My budget**, **Upcoming bills**, **Subscriptions**, **Net worth**, **Household**,
  **Calendar**, **Timeline** and **Where my money goes**.
- **Assistant** (⌘J), optional: your own Claude Code, Codex or opencode, or an Ollama model on your
  computer, reads the open book; every change it suggests is a card you accept (⌘Z undoes it).
- In Spanish, English, Portuguese and French.

## Download and install

Requirements: **macOS 11 or later on an Apple silicon Mac** (M1 or later). There is no version for
Intel Macs, Windows or Linux yet.

1. Download **[expense-me-macos-arm64.zip](https://github.com/otherwisetech/expense-me-releases/releases/latest/download/expense-me-macos-arm64.zip)**
   (or pick a version under [Releases](https://github.com/otherwisetech/expense-me-releases/releases)).
2. Open the `.zip` and drag **expense me** into your **Applications** folder.
3. **The first time**, right-click (or Control-click) **expense me** → **Open** → **Open**.
   The app is signed *ad hoc* and isn't notarized by Apple, which is why macOS asks. If macOS only
   offers "Done" or "Move to Trash" (macOS 15 or later), go to **System Settings → Privacy & Security**
   and click **Open Anyway**. After that it opens normally. If you update from 0.3.17 or earlier, macOS may ask one last time
   for keychain access, to move your saved passwords: choose "Always Allow". From 0.3.18 on,
   expense me keeps them in a file on your computer that only your user can read, and doesn't ask
   again.

You can also install it and keep it up to date with **Otherwise Hub**, the free installer for
Otherwise apps ([otherwisetech.com](https://otherwisetech.com)).

To verify the download, each release includes a `.sha256` file:

```
shasum -a 256 -c expense-me-macos-arm64.zip.sha256
```

## Privacy: your data stays on your computer

- Your books (receipts, statements, transactions) are stored in a folder on your computer that you
  choose (it can be, for example, a OneDrive folder). There is no Otherwise account or server.
- expense me doesn't send your data to Otherwise or anyone else. It only goes online when you ask it
  to: the mail server you set up to receive receipts, "Get today's rate online" (it sends only the
  currency pair and the date) and, if you use it, the assistant: whatever your AI tool reads goes to
  that tool's provider, unless you use Ollama on your computer.
- Notifications don't show merchants or amounts unless you turn that on in Settings.

## Report a problem or request a feature

Open an [issue](https://github.com/otherwisetech/expense-me-releases/issues/new/choose) using the bug
or feature form. **Issues are public: never include personal or real financial data** (names,
amounts, account or card numbers, statements, receipts, paths on your computer). Cover that data in
screenshots. We will never ask for your book or your statements.

For a security vulnerability, don't open an issue: read [SECURITY.md](SECURITY.md).

## License

Proprietary software, free to use. © 2026 Otherwise Technologies LLC, Wyoming, USA. All rights
reserved. See [LICENSE](LICENSE). Third-party components keep their own licenses:
[THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md). Changes by version (in Spanish):
[CHANGELOG.md](CHANGELOG.md).
