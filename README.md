# Job Scout Agent

An AI agent built with Claude Code that scans the career pages of a fixed list of tech
companies and returns a shortlist of relevant Business / Program / Product Operations roles
in Israel — filtering out noise, avoiding duplicates, and reporting only (a human decides
whether to apply).

## What it does
- Monitors a defined list of 11 target companies.
- Matches roles by meaning, not just exact title (e.g. "BizOps Lead" counts as relevant).
- Excludes noise (e.g. Product Manager is not Program Manager).
- Remembers what it already reported (seen-jobs.json) so it never repeats a posting.
- Human-in-the-loop: reports a shortlist, never applies.

## How to run
Open the project in Claude Code and ask:
> use the job-scout agent to check for new relevant jobs
