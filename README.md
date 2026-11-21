# GILRUON harness mail

GILRUON harness mail is a small, private tool. It lets the GILRUON harness, a personal automation project, send short fixed alert mails from its own Gmail account to the account owner. For example, it reports that a run has stopped or that a scheduled job has not run.

## Privacy policy

- **Scope:** The app asks for one Google permission, `https://www.googleapis.com/auth/gmail.send`, which lets it send mail. It does not read, search, label or delete mail. It does not access contacts, calendars, files or any other Google data.
- **Data used:** The only data it handles is the alert text the harness writes and the recipient address the owner set. Nothing is collected from other people.
- **Storage:** The OAuth credential is kept in one file (mode 0600) on the owner's own server. It is not shared with anyone or sent anywhere except Google's token and Gmail send endpoints.
- **Sharing:** No data is sold, shared or used for advertising.
- **Revoking access:** The owner can revoke access at any time at https://myaccount.google.com/permissions.
- **Contact:** Open an issue on this repository.

## Terms

This tool is provided as is, for the owner's personal use only.
