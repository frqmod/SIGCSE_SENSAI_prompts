# SENSAI System Prompts

Supplementary material for *Do Newer Models Make Better Tutors?: Characterizing Real-World Failures of AI Tutors in Higher Education Across Two Years, Two Prompts, and Five Models* (SIGCSE TS '27).

These are the two system prompts used by SENSAI, the AI tutor studied in the paper. `v1.md` is the original prompt for gpt-4o and gpt-5, and `v2.md` contains the effort-gated prompt used with gpt-5.1, gpt-5.2, and gpt-5.4.

`{challenge_description}` and `$CHALLENGE_DESCRIPTION` are placeholders filled in with each challenge's description at runtime. The double braces in `v1.md` (`pwn.college{{...}}`) are template escaping and render as `pwn.college{...}`.
