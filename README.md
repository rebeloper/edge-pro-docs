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
bash <(curl -fsSL https://edge-api-v2.rebeloper.workers.dev/edge-pro-installer.sh)
```

Paste your license key when prompted. This installs all 9 skills into `~/.claude/skills/`.

Avoid passing the key as `--key <key>` on the command line — it can end up in your shell history. (The flag still works if you need it in a non-interactive/scripted context, e.g. `--key <your-license-key>`.)

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
