# Security Policy

Skuvra is source-available so people can inspect how it handles sensitive local
maintenance tasks.

## Supported Versions

Only the latest official release and the current main branch are considered for
security fixes while the project is early.

## Reporting a Vulnerability

Please report security and privacy issues responsibly.

Preferred options:

- Use GitHub Security Advisories for this repository if available.
- If private reporting is not available, open a public issue with a minimal
  description and ask for a private contact path before posting exploit steps.

Please do not post:

- passwords, cookies, tokens, browser contents, private files, or personal data;
- working exploit chains for destructive behavior; or
- details that would help others harm users before there is a chance to fix the
  issue.

Useful reports include:

- affected Skuvra version or commit;
- Windows version;
- feature or action involved;
- expected behavior;
- actual behavior;
- impact;
- safe reproduction steps; and
- screenshots or logs with private data removed.

## Scope

In scope:

- unintended deletion or modification without clear confirmation;
- browser secret, cookie, token, credential, or browsing-content exposure;
- unsafe registry, startup, scheduled-task, process, update, or wipe behavior;
- local privilege, path traversal, command injection, or unsafe subprocess use;
- insecure backup/log handling; and
- misleading UI that could cause users to confirm a high-impact action without
  understanding it.

Out of scope:

- social engineering unrelated to Skuvra;
- issues in unofficial builds or modified forks;
- issues caused only by bypassing Skuvra's confirmations or modifying source
  code locally; and
- reports that require destructive testing without prior coordination.
