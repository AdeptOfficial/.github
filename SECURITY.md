# Security policy

This policy covers every public repository under github.com/AdeptOfficial, including the
self-hosted apps (AMP Watchdog, Domain Watcher, Status Tracker, ConnectHub), the websites,
and Uplink, the account platform planned for app.adeptproductions.dev. A repository with its
own SECURITY.md overrides this file.

## Reporting a vulnerability

Please do not open a public issue for a security problem.

- Preferred: the **Report a vulnerability** button on the repository's Security tab. It
  opens a private advisory only I can see.
- Or email **hello@adeptproductions.dev** with "security" in the subject.

Include what you found, where (repository, version or commit), how to reproduce it, and
what an attacker could do with it. A proof of concept helps. If you need to share
something sensitive, say so and I will set up a safer channel.

## What to expect

- Acknowledgement within 72 hours.
- An assessment and a plan within 7 days.
- A fix released as fast as the severity demands. Account and credential handling in
  Uplink comes first.
- Credit in the release notes if you want it, anonymity if you prefer.

I ask for coordinated disclosure: give me a reasonable window to ship a fix before
publishing details.

## Supported versions

Only the latest release of each project, or `main` where no release exists, receives
security fixes. Self-hosted apps are run by their operators; keep your instance updated.

## Out of scope

- Misconfiguration of an instance you run yourself (exposed ports, weak passwords, no TLS).
- Issues in upstream dependencies that are already public; report those upstream, but tell
  me if a pinned version needs bumping.
- Volume-based attacks against my own hosted services.

## Scope note on the websites

adeptproductions.dev and me.adeptproductions.dev are static sites. Findings about their
headers, CSP or build pipeline are welcome through the same channels.

// code-signed by AdepT_X
