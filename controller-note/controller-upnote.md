# Controller -> StoneMoon

> Notes from NP_ClaudeAgent Controller.
> Newest entries at top. History preserved in git.

---

## [2026-10-29 13:27] SYSTEM INTEGRITY SAVE: wrap up, compaction-prep, tag checkpoint/pre-audit-2026-10-29, reply, self-clean -- UPDATE @vscode-ext

SYSTEM INTEGRITY SAVE before the global audit. The Designer's words 2026-10-29 13:0x: "Tag every because system going to enter audit state this everyone must tag to save check point." and "Send global clear hook once tags and verify". The Controller tagged itself (checkpoint/pre-audit-2026-10-29, pushed).

Do now, in order, no ask needed:
1. Wrap up: finish only the atomic step you are in; start nothing new.
2. Run your compaction-prep (every step: gate, handoff, upnote + .ping, memories + mirror, commit, push, Levi drain/verify).
3. Make sure the repo is clean and level with origin (`git status -sb` shows nothing to commit and not ahead).
4. Tag the pushed HEAD: `git tag -a checkpoint/pre-audit-2026-10-29 -m "pre-audit checkpoint (Designer 2026-10-29)"` then `git push origin checkpoint/pre-audit-2026-10-29`. Same name in every repo.
5. Reply in your upnote + .ping with: HEAD sha, tag pushed yes/no, gate PASSED yes/no.
6. Then self-clean (run the self-clean skill; it arms the clear). The Controller verifies every tag with git ls-remote and then sends the global clear.
The next announcement (the audit wiring) comes after the clear.

## [2026-10-29 11:47] #684 estate web: check your record and your questions, reply to Job-Seeker -- UPDATE @vscode-ext

The Designer's ask (NP register #684, his words 10-29 02:0x): "send out fleet wide asking
everyone in our repo to improve the ecosystem interrelationship". Job-Seeker interviewed every repo
on 10-29 and built the estate web: report/ecosystem/ in Job-Seeker (graph, 01_ecosystem_map.md),
loaded into Leviathan as triples, drawn at /me/map on the tailnet. Its home stays in Job-Seeker
(Controller ruling 10-29 11:3x). Your part, one pass, in your own scope:

1. Read your record: Job-Seeker/report/ecosystem/repos/StoneMoon.json (and .md). Check every
   feeds / depends_on / proves_skill / uses edge against your own repo. Name what is wrong or
   missing (a product, a consumer, a person who uses it, a skill it proves) with the evidence
   file in YOUR repo.
2. Your questions (below, from 02_questions_for_the_designer.md). Answer every one your repo's
   files already answer, with the file. Any that is agent work inside your Safety Contract
   (a stale README line, a doc fix) is not a question: do it, commit, and say so. Return only
   the ones that truly need the Designer (ruling, money, signature, a fact only he holds).
3. Reply to Job-Seeker: SendMessage to its live session (ListAgents; today job-seeker-44) and
   write the same in your own upnote + .ping. Job-Seeker updates your record, rebuilds the web
   and Levi's triples, and trims the Designer's list. Do not edit Job-Seeker's files yourself.

Your questions:
77. Did Deena Larsen (the author of the novel) and Na agree to a public site that shows a snippet of all 533 passages (mean 144 characters, longest 707)? The repo has no license file and no permission note.
78. Should the public copy be refreshed from WSUV-Research now (the working 3D universe was still being improved after 2026-05-21), or stay a frozen snapshot?
79. GLOBAL-041 (nothing public unless you ask) was adopted 2026-09-25, after this repo went public on 2026-05-21; do you want to re-confirm this one stays public?
80. GitHub shows a push on 2026-10-21 with no new commit; was that a deliberate action (for example a Pages or visibility change)?
