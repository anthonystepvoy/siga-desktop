# Security Policy

## Reporting a Vulnerability

If you find a security issue in SIGA Code, **do not open a public issue**.

Email **contact@siga.codes** with:

- A clear description of the vulnerability
- Steps to reproduce
- Affected SIGA version
- Your assessment of impact

I'll acknowledge within 72 hours and aim to ship a patch within 7 days for
critical issues. Once a fix is shipped, you'll be credited in the release
notes (with your permission).

## Scope

In scope:
- The SIGA desktop application (this repository's installers)
- Authentication flow against `api.siga.codes`
- Plan-enforcement bypass
- Sandbox escape (agents accessing files outside the selected project folder)

Out of scope:
- Social engineering attacks against SIGA users
- Physical access to a user's machine
- Issues in upstream CLI tools (claude-code, gemini-cli, codex, etc.) — please
  report those to their respective maintainers
- Denial-of-service attacks that require unrealistic traffic volume

## Hall of fame

Reporters who responsibly disclose serious issues are listed here:

_(none yet — be the first)_
