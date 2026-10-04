<div align="center">

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/wattle-cloud-logo-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/wattle-cloud-logo-light.svg">
  <img alt="Wattle Cloud" src="assets/wattle-cloud-logo-light.svg" width="440">
</picture>

<br>
<br>

### Websites, apps, databases and game servers, hosted in Brisbane and the UK.

Simple to deploy. One monthly price in AUD or GBP. Support from a real person.

<br>

[**Website**](https://wattlecloud.com) &nbsp;·&nbsp; [**Pricing**](https://wattlecloud.com/pricing/) &nbsp;·&nbsp; [**Docs**](https://wattlecloud.com/docs/) &nbsp;·&nbsp; [**Discord**](https://discord.gg/wattlecloud) &nbsp;·&nbsp; [**Join the waitlist**](https://wattlecloud.com/waitlist/)

<br>

</div>

> [!NOTE]
> **The waitlist is open.** Brisbane first, UK next. Public sign-up opens at launch, and everyone on the waitlist gets an email when their region opens. Joining is free and needs no card.

<br>

## About us

Wattle Cloud is an independent hosting platform from Brisbane, Australia. We host websites, apps, Discord bots, managed databases and game servers, in Brisbane and the UK.

We built it because Australian developers have been left out. Railway, Render and Koyeb have no Australian region, so Australian apps on them usually run in Singapore, adding about 95 ms to every round trip from the east coast. We wanted that same simple deploy experience close to home, priced in local currency, without the surprise bills.

Wattle Cloud isn't a reseller or a panel on top of someone else's cloud. Every part of the platform, from the build pipeline and the edge to the database backups, is built and run by us.

### Our four promises

<table>
<tr>
<td width="50%" valign="top">

**No surprise bills**<br>
One price a month for your plan, with no usage charges on top. A busy month costs the same as a quiet one.

</td>
<td width="50%" valign="top">

**Local**<br>
Servers close to your users, with prices in Australian dollars or British pounds.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**A real person answers**<br>
Support comes from a person, not a bot. Pro plans get priority.

</td>
<td width="50%" valign="top">

**No lock-in**<br>
Export any database at any time. Deploys use standard Docker images. Your data, your code, your call.

</td>
</tr>
</table>

<br>

## What we host

| | What it is | Brisbane | UK |
| --- | --- | :---: | :---: |
| **Websites and apps** | Anything from a static site to a full SaaS, from GitHub or a Docker image | At launch | Coming soon |
| **Databases** | Managed, backed up, with point-in-time restore | At launch | Coming soon |
| **Discord bots** | Always-on bots that sit next to their database | At launch | Coming soon |
| **Game servers** | Minecraft, Garry's Mod and Rust, on our own game panel | To follow | At launch |

**Runs whatever you build:** static sites, Next.js, WordPress, Laravel, Django, Express, Go, Ghost, n8n, Umami, APIs, Discord bots and any Docker image.

<br>

## The platform

<table>
<tr>
<td width="50%" valign="top">

#### Deploy
- Every push to GitHub deploys, or ship any Docker image
- Builds detected for you, or use your own Dockerfile
- Zero-downtime deploys: a new version only gets traffic once its health check passes
- Pre-deploy commands for migrations, and one-click rollback
- Static sites, background workers and cron jobs
- One-click templates for WordPress, Ghost, n8n and Umami

</td>
<td width="50%" valign="top">

#### Databases
- PostgreSQL 18, MySQL 8.4, MariaDB 11.8, Valkey 8 (Redis-compatible) and ClickHouse
- Point-in-time backups and restore, with encrypted off-site copies
- Restores tested every week, on real machines
- Data browser, SQL console and one-click export
- Encrypted access through the `wattle` CLI, with no database port open to the internet

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Networking
- Every app gets its own address at `name.wattlecloud.com`
- Custom domains with automatic HTTPS
- Private networking: apps reach databases at `name.internal`
- All traffic comes in through Cloudflare, nothing else is exposed

</td>
<td width="50%" valign="top">

#### Security
- Apps run in a gVisor sandbox, each environment on its own network
- Builds run in their own micro-VMs
- Two-factor sign-in, passkeys and recovery codes
- Workspaces with roles, invites and an audit log

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### Logs and monitoring
- Live logs and log search
- HTTP request logs and metrics
- Alerts, out-of-memory notices and signed webhooks

</td>
<td width="50%" valign="top">

#### For developers and AI agents
- The `wattle` CLI
- A public API
- An MCP server for AI coding tools

</td>
</tr>
</table>

<br>

## How it works

1. **Connect GitHub.** Every push deploys automatically, or use a Docker image instead.
2. **Deploy.** We build your app and start it in Brisbane with zero downtime. Roll back any time.
3. **Done.** Your app is live with HTTPS. Add a database or your own domain whenever you like.

<br>

## Pricing

| Plan | Australia | United Kingdom | Made for |
| --- | --- | --- | --- |
| **Hobby** | A$8 a month | £4 a month | Side projects, client sites and bots |
| **Pro** | A$30 a month per workspace | £15 a month per workspace | Teams and production, with unlimited seats, 7-day point-in-time restore and priority support |

Every plan includes database backups and export, zero-downtime deploys and rollbacks, private networking, logs, metrics and alerts, and a web address for every app. No usage charges on top.

Plan sizes are still being finalised and will be listed before launch. See [wattlecloud.com/pricing](https://wattlecloud.com/pricing/) for the latest.

<br>

## Wattle Bot

**One Discord bot to run your whole server.** Moderation, auto-mod, logging, welcome messages, levels, role menus, custom commands, tickets, giveaways, polls, music, text to speech and more, all set up from one dashboard. Made by Wattle Cloud.

[**Add Wattle Bot** at bot.wattlecloud.com](https://bot.wattlecloud.com)

<br>

## Trust and safety

- **Report abuse** (phishing, malware, spam or illegal content hosted with us) at [app.wattlecloud.com/report](https://app.wattlecloud.com/report) or [abuse@wattlecloud.com](mailto:abuse@wattlecloud.com).
- **Found a security issue?** Email [support@wattlecloud.com](mailto:support@wattlecloud.com) with "Security" in the subject. Please don't open a public issue.
- **Our policies:** [Terms](https://wattlecloud.com/legal/terms/) · [Acceptable use](https://wattlecloud.com/legal/acceptable-use/) · [Privacy](https://wattlecloud.com/legal/privacy/) · [Cookies](https://wattlecloud.com/legal/cookies/) · [Refunds](https://wattlecloud.com/legal/refunds/)

<br>

## Get in touch

- **Website:** [wattlecloud.com](https://wattlecloud.com)
- **Support:** [support@wattlecloud.com](mailto:support@wattlecloud.com)
- **Community:** [discord.gg/wattlecloud](https://discord.gg/wattlecloud)
- **Waitlist:** [wattlecloud.com/waitlist](https://wattlecloud.com/waitlist/)

<br>

<div align="center">
<sub>Made in Brisbane, Australia. © 2026 Wattle Cloud.</sub>
</div>
