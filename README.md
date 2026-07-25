# MailKite Community

Questions, ideas, and show-and-tell for **[MailKite](https://mailkite.dev)** — the email
platform for developers and their teams. Receive email as a webhook, send with one API,
give your agents their own inbox.

### **[→ Open a discussion](https://github.com/mailkite/community/discussions)**

## Where to go

| I want to… | Go to |
|---|---|
| Ask how to do something | [Discussions → Q&A](https://github.com/mailkite/community/discussions) |
| Request a feature, an SDK, or an integration | [Discussions → Ideas](https://github.com/mailkite/community/discussions) |
| Show what you built | [Discussions → Show and tell](https://github.com/mailkite/community/discussions) |
| Report a bug in a library | That library's repo → Issues (see the tables below) |
| Read the docs | [mailkite.dev/docs](https://mailkite.dev/docs) |
| Check platform health | [mailkite.dev/status](https://mailkite.dev/status) |
| Reach a human privately | [mailkite.dev/contact](https://mailkite.dev/contact) |

> **Heads-up on pull requests.** Every library below is developed in a private monorepo and
> published to its public repo as a **read-only release mirror**. PRs opened against a mirror
> can't be merged. Open a discussion here or an issue on the mirror — the fix lands upstream
> and ships with the next release.

---

## Docs

| | |
|---|---|
| [Quickstart](https://mailkite.dev/docs/quickstart) | First send + first webhook in about five minutes |
| [Receiving email](https://mailkite.dev/docs/receiving) | Inbound routes → webhook, forward, store, drop, agent |
| [Sending email](https://mailkite.dev/docs/sending) | Transactional mail, replies, broadcasts |
| [API reference](https://mailkite.dev/docs/api-reference) | Every endpoint, every field |
| [Libraries](https://mailkite.dev/docs/libraries) | Install + first call in each language |
| [AI agents](https://mailkite.dev/docs/ai-agents) | MCP server, agent inboxes, scoped access |
| [Inbox agents](https://mailkite.dev/docs/inbox-agents) | Auto-reply: triage, answer, tag, escalate |
| [Domains](https://mailkite.dev/docs/domains) | MX, SPF, DKIM, DMARC — what we set and why |
| [Webhook security](https://mailkite.dev/docs/webhook-security) | Verifying the HMAC-SHA256 signature |
| [Webhook delivery](https://mailkite.dev/docs/webhook-delivery) | Retries, replay, delivery logs |
| [SMTP relay](https://mailkite.dev/docs/smtp-relay) · [IMAP](https://mailkite.dev/docs/imap) | Use your existing mailer or mail client |
| [CLI](https://mailkite.dev/docs/cli) | `mailkite` on the command line |
| [Authentication](https://mailkite.dev/docs/authentication) | API keys, scopes, OAuth |
| [Data & privacy](https://mailkite.dev/docs/data-privacy) | Retention, zero-retention passthrough |

---

## Server SDKs

One API shape across every language.

| Language | Package | Repo |
|---|---|---|
| Node.js / TypeScript | `mailkite` (npm) | [mailkite-node](https://github.com/mailkite/mailkite-node) |
| Python | `mailkite-dev` (PyPI) | [mailkite-python](https://github.com/mailkite/mailkite-python) |
| PHP | `mailkite/mailkite` (Packagist) | [mailkite-php](https://github.com/mailkite/mailkite-php) |
| Ruby | `mailkite` (RubyGems) | [mailkite-ruby](https://github.com/mailkite/mailkite-ruby) |
| Java | `dev.mailkite:mailkite` (Maven Central) | [mailkite-java](https://github.com/mailkite/mailkite-java) |
| Go | `github.com/mailkite/mailkite-go` | [mailkite-go](https://github.com/mailkite/mailkite-go) |
| .NET | `MailKite` (NuGet) | [mailkite-dotnet](https://github.com/mailkite/mailkite-dotnet) |
| Rust | `mailkite` (crates.io) | [mailkite-rust](https://github.com/mailkite/mailkite-rust) |
| Elixir | `mailkite` (Hex) | [mailkite-elixir](https://github.com/mailkite/mailkite-elixir) |

## Client SDKs

For apps that talk to MailKite directly, over OAuth 2.1 + PKCE — no server key in the client.

| Platform | Package | Repo |
|---|---|---|
| JS / browser | `@mailkite/client` (npm) | [mailkite-js](https://github.com/mailkite/mailkite-js) |
| Swift / iOS | `MailKiteClient` (SwiftPM) | [mailkite-swift](https://github.com/mailkite/mailkite-swift) |
| Kotlin / Android | `dev.mailkite:mailkite-client` | [mailkite-kotlin](https://github.com/mailkite/mailkite-kotlin) |
| Flutter | `mailkite_client` (pub.dev) | [mailkite-flutter](https://github.com/mailkite/mailkite-flutter) |
| Expo / React Native | `@mailkite/expo` (npm) | [mailkite-expo](https://github.com/mailkite/mailkite-expo) |

## Command line & agents

| | |
|---|---|
| [mailkite-cli](https://github.com/mailkite/mailkite-cli) | `@mailkite/cli` — send, tail inbound, manage domains and keys |
| [homebrew-tap](https://github.com/mailkite/homebrew-tap) | `brew install mailkite/tap/mailkite` |
| [mailkite-mcp](https://github.com/mailkite/mailkite-mcp) | `@mailkite/mcp` — local MCP server |
| [claude-code](https://github.com/mailkite/claude-code) | Official Claude Code plugin — hosted MCP over OAuth, no key to copy |
| [agent-skills](https://github.com/mailkite/agent-skills) | `npx skills add mailkite/agent-skills` — skills for coding agents |

---

## Boilerplates & templates

Start from a working app, not an empty file.

| | |
|---|---|
| [mailkite-nextjs-inbox](https://github.com/mailkite/mailkite-nextjs-inbox) | Zero-database Next.js inbox — receive, read, reply. One-click Vercel deploy. |
| [mailkite-inbound-inbox](https://github.com/mailkite/mailkite-inbound-inbox) | Deploy-anywhere inbound inbox — Cloudflare, Railway, Render, Fly, DO |
| [saas-startup](https://github.com/mailkite/saas-startup) | Next.js SaaS starter with email wired in |
| [mail](https://github.com/mailkite/mail) · [webmail](https://github.com/mailkite/webmail) | Open-source MailKite email client — web, desktop, mobile |

## Examples

| | |
|---|---|
| [mailkite-examples](https://github.com/mailkite/mailkite-examples) | **Start here** — runnable send / receive-as-webhook / agent-inbox examples across 30+ stacks: Next.js, Nuxt, Astro, Remix, Express, Hono, Bun, Deno, Cloudflare Workers, Vercel Functions, AWS Lambda, Django, Flask, FastAPI, Rails, Sinatra, Laravel, Symfony, Spring Boot, Go, Supabase Edge Functions, SMTP, IMAP, REST, and the CLI |
| [mailkite-nodejs-send-email-example](https://github.com/mailkite/mailkite-nodejs-send-email-example) | The smallest possible send |
| [demo-programmable-email](https://github.com/mailkite/demo-programmable-email) | One account, one key, many domains — the setup you copy into every project |
| [demo-email-agent-tool](https://github.com/mailkite/demo-email-agent-tool) | Three ways to give an agent email: MCP, the SDK, or your own webhook |
| [demo-programmable-email-for-agents](https://github.com/mailkite/demo-programmable-email-for-agents) | An agent inbox on your domain — the receive→think→reply loop |

## Framework & platform integrations

| | |
|---|---|
| [laravel](https://github.com/mailkite/laravel) | Mail transport — set `MAIL_MAILER=mailkite` |
| [nuxt-mailkite](https://github.com/mailkite/nuxt-mailkite) | Nuxt module — inbound webhooks + sending |
| [astro-mailkite](https://github.com/mailkite/astro-mailkite) | Astro integration (SSR) |
| [nodemailer-mailkite-transport](https://github.com/mailkite/nodemailer-mailkite-transport) | Send through MailKite from any Nodemailer app |
| [supabase-mailkite](https://github.com/mailkite/supabase-mailkite) | Edge Functions — inbound email as rows, transactional out |
| [pipedream](https://github.com/mailkite/pipedream) | Inbound email Source + Send action |
| [send-email-action](https://github.com/mailkite/send-email-action) | GitHub Action — send mail, and trigger workflows from inbound email |
| [forge](https://github.com/mailkite/forge) · [ploi](https://github.com/mailkite/ploi) · [runcloud](https://github.com/mailkite/runcloud) | One-command CLIs to wire MailKite into a managed host |

## Libraries

Standalone pieces we built for MailKite and released on their own.

| | |
|---|---|
| [mail-parse](https://github.com/mailkite/mail-parse) | Streaming, memory-efficient, fully-typed MIME parser with a declarative middleware seam |
| [mail-parse-py](https://github.com/mailkite/mail-parse-py) · [mail-parse-go](https://github.com/mailkite/mail-parse-go) | Ports with cross-language failure-signature hash parity |

---

## Alternative demos

Each one is a runnable MailKite **receive → verify → think → reply** loop sitting next to the
same job done on another provider, so you can diff and test the gap yourself. Most run with
no account and no LLM.

[agentmail](https://github.com/mailkite/demo-agentmail-ai-agent) ·
[amazon-ses](https://github.com/mailkite/demo-amazon-ses-ai-agent) ·
[brevo](https://github.com/mailkite/demo-brevo-ai-agent) ·
[cloudflare-email-routing](https://github.com/mailkite/demo-cloudflare-email-routing-ai-agent) ·
[elastic-email](https://github.com/mailkite/demo-elastic-email-ai-agent) ·
[gmail-api](https://github.com/mailkite/demo-gmail-api-ai-agent) ·
[loops](https://github.com/mailkite/demo-loops-ai-agent) ·
[mailersend](https://github.com/mailkite/demo-mailersend-ai-agent) ·
[mailgun](https://github.com/mailkite/demo-mailgun-ai-agent) ·
[mailjet](https://github.com/mailkite/demo-mailjet-ai-agent) ·
[mandrill](https://github.com/mailkite/demo-mandrill-ai-agent) ·
[microsoft-graph](https://github.com/mailkite/demo-microsoft-graph-ai-agent) ·
[nylas](https://github.com/mailkite/demo-nylas-ai-agent) ·
[postal](https://github.com/mailkite/demo-postal-ai-agent) ·
[postmark](https://github.com/mailkite/demo-postmark-ai-agent) ·
[resend](https://github.com/mailkite/demo-resend-ai-agent) ·
[sendgrid](https://github.com/mailkite/demo-sendgrid-ai-agent) ·
[smtp2go](https://github.com/mailkite/demo-smtp2go-ai-agent) ·
[socketlabs](https://github.com/mailkite/demo-socketlabs-ai-agent) ·
[sparkpost](https://github.com/mailkite/demo-sparkpost-ai-agent) ·
[zeptomail](https://github.com/mailkite/demo-zeptomail-ai-agent)

---

## Ground rules

Be decent to each other. Search before posting — someone may have hit it already. When you
report a problem, include the library and version, what you expected, and what happened; a
message ID or request ID gets you an answer much faster. Don't paste API keys, tokens, or real
recipients' addresses into a public thread — [contact us](https://mailkite.dev/contact) for
anything account-specific.

MailKite is free to start — unlimited domains, no credit card.
**[Get an API key →](https://app.mailkite.dev)**
