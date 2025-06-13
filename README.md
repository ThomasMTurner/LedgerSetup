# LedgerSetup
Includes ledger for Cambridge 2025 for personal finance management using Ledger plaintext accounting.

## Notes for using Ledger.

`ledger -f file_name` is used to run commands. However, we can also specify the ledger file using an environment variable  `LEDGER_FILE=file_name`. Set this environment variable when we change workstation \[transferring to ARM hardware\].

## General Notes Related to Budgeting.

- [Ledger Documentation](https://howeyc.github.io/ledger/02_Balance.html).
- Currently, Savings is a singular Asset. I want to make this more fine-grained. This isn't necessary for now, but check on this somewhat regularly. For example, if I want to save for a holiday with Sultan, Chris, and others, then I ought to make a separate Asset for this purpose. This is a manifestation of out-of-sight out-of-mind, baby.
- Research appropriate savings instruments. Currently, the Savings Asset will be collected in my Barclays instant-access savings account. However, this likely is low-interest. Again, researching this at some point would be good.
- Until we setup an environment variable, the following command can be used to list all accounts, including those with zero balance: `ledger -f thomas-turner.ledger accounts -E`.
- Dates for Gym and Judo payments are tentative. Change to the actual recurring direct debit payment dates.
- This budget is up-to-date until **January**.
