# Mamansh marketing: always use Mamansh Brain

Whenever a task touches Mamansh marketing (Meta ads, creatives, ad copy, briefs, customer reviews or comments, testimonials, campaign analysis), use the team knowledge base **[pankajagg/mamansh-brain](https://github.com/pankajagg/mamansh-brain)** as the source of truth, and update it when the work is done.

## 1. Get it
- **Cloud session:** if `/home/user/mamansh-brain` is missing, attach the repo with the `add_repo` tool (owner `pankajagg`, repo `mamansh-brain`, access `push`), clone it to `/home/user/mamansh-brain`, then register it with `register_repo_root`.
- **Local:** use your local clone and `git pull` first.

Follow `mamansh-brain/CLAUDE.md`. It says what may and may not be stored there. No finance, P&L, revenue or settlement figures, no customer personal data, no API keys.

## 2. Reference it before working
Start from `mamansh-brain/README.md` (the index), then read what the task needs:
- `performance/meta-ads-performance-reference.md`: winners, angles, products, naming convention
- `customer-voice/customer-voice-reference.md` and `customer-voice/testimonial-quotes-*.md`: complaints, praise, FAQs, verbatim quotes
- `references/static-ads/ai-static-ads-masterclass.md`: creative playbook, personas, guardrails
- `references/static-ads/swipe-file/README.md`: competitor swipe file
- `creatives/*/brief.md`: past briefs and what was generated

Don't contradict the brain silently. If the new work disagrees with it, say so and update it.

## 3. Update it after working
Before finishing a marketing task:
1. Write what you learned or made into the right file. Update existing references in place, and add new dated files (e.g. `performance/snapshots/YYYY-MM-DD.md`, `creatives/<name>-YYYY-MM/brief.md`) for new snapshots or creative batches.
2. Add a row to the table in `README.md` for any new top-level item.
3. Check the "What never goes here" list in `mamansh-brain/CLAUDE.md` before committing.
4. Commit with a clear message and push to `main` of `mamansh-brain`.
5. Tell the user what you changed in the brain.

# Other knowledge bases

- **[real-simple-labs/parker-brain](https://github.com/real-simple-labs/parker-brain)**: knowledge base for Parker. When a task involves Parker, attach it with `add_repo` (owner `real-simple-labs`, repo `parker-brain`), clone it to `/home/user/parker-brain`, register it with `register_repo_root`, and start from its README and CLAUDE.md.
