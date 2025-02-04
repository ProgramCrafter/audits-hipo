# Hipo Protocol Audits

## 2023-10 [TonTech](https://ton.tech/) Hipo Audit Report

The team reported a total of 5 issues:

- Low Risk Issues: 4 (2 Resolved)
- Informational Issues: 1 (1 Resolved)

See [full report](TonTech%20Hipo%20Audit%20Report%202023-10.pdf) for more details.

### Unresolved Issues

- **Missing late participation check**: There is a check for late participation and even in the case of a network stop and restart after the participation time, there will be no harm to the protocol, only borrowers will skip that round.

- **Missing sender checks**: To make the protocol permission-less, the `stake_coins` and `withdraw_tokens` messages can be sent by anyone willing to pay the gas fee. Usually the driver will send these messages, but anyone can also send these, so in case the driver stops working, users can withdraw their funds.

## 2023-10 Daniil Sedov Hipo Audit Report

Daniil reported a total of 4 issues:

- Minor Issues: 1 (1 Resolved)
- Informational Issues: 3 (3 Resolved)

See [full report](Daniil%20Sedov%20Hipo%20Audit%20Report%202023-10.pdf) for more details.

## 2024-03 [ProgramCrafter](https://ratingers.pythonanywhere.com) Hipo Audit Report

ProgramCrafter reported a total of 9 issues:

- Critical Issues: 1 (1 Resolved)
- Major Issues: 1 (1 Resolved)
- Medium Issues: 3 (2 Resolved, 1 Withdrawn)
- Minor Issues: 3 (3 Resolved)
- Informational Issues: 1 (1 Resolved)

See [full report](ProgramCrafter%20Hipo%20Audit%20Report%202024-03.pdf) for more details.
