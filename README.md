# EdgePro

EdgePro is a set of 9 Claude Code skills for deeper learning and review, sold as a one-time purchase:

- `edge-pro-capture` — harvest flashcards from a conversation or source
- `edge-pro-challenge` — stress-test a plan or design
- `edge-pro-create` — turn one fact into a flashcard
- `edge-pro-deck` — browse/edit/remove flashcards
- `edge-pro-learn` — Socratic code walkthroughs
- `edge-pro-mentor` — multi-session guided learning
- `edge-pro-quiz` — spaced-repetition quiz drills
- `edge-pro-review` — Socratic PR review
- `edge-pro-solve` — Socratic problem solving

## Install

After purchase you'll receive a license key by email. Run:

```bash
bash <(curl -fsSL https://edge-api-v2.rebeloper.workers.dev/edge-pro-installer.sh) --key <your-license-key>
```

This installs all 9 skills into `~/.claude/skills/`.

## Update

```bash
bash <(curl -fsSL https://edge-api-v2.rebeloper.workers.dev/edge-pro-installer.sh) --update
```

## Check for updates

```bash
bash <(curl -fsSL https://edge-api-v2.rebeloper.workers.dev/edge-pro-installer.sh) --status
```

Reports whether a newer version is available, without installing it.

## Uninstall

```bash
bash <(curl -fsSL https://edge-api-v2.rebeloper.workers.dev/edge-pro-installer.sh) --uninstall
```

Removes all 9 skills. Your license key stays valid — reinstall any time.

## Lost your license key?

```bash
bash <(curl -fsSL https://edge-api-v2.rebeloper.workers.dev/edge-pro-installer.sh) --reset-key
```

Enter the email you purchased with; if it matches, the key is resent.

## Notes

- The license key is a purchase gate, not a per-machine activation — no machine limits or transfer flow.
- Questions: reply to your purchase email.
