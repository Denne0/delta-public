# Delta: public files

Delta is a post-session study tool for poker players. Its code is private; this repository only
holds the files Delta reads from the internet:

- `revocations.json`: the list of cancelled license keys, signed by the owner. It holds scrambled
  fingerprints only (no key ids, names or machine codes), and Delta ignores any list the owner
  didn't sign.

Installers and a download page may be added here later.
