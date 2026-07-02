# P4-Product-Design

Internal home for Swolverine's design-to-code tooling — Claude Code/Desktop plugins that turn Figma designs into production-ready code, plus other team automation as it gets built.

## Getting access

Repos here are private. To get in:

1. **Message Chance with your GitHub username** and ask for an invite to the org.
2. You'll get an email with an invite link — accept it (expires after 7 days, so ping again if it lapses).
3. Once you're in, follow **Setup** below. Everything past this point is self-service — you shouldn't need to ask anyone anything else to get running.

## Setup (do this once, after joining)

### 1. Authenticate git to GitHub on your machine

Our repos are private, so your computer needs a way to prove it's you when it fetches them — being an org member alone isn't enough.

Easiest path: install the [GitHub CLI](https://cli.github.com) if you don't have it, then run:

```
gh auth login
```

Follow the prompts (choose GitHub.com, HTTPS, and log in via your browser). An SSH key added to your GitHub account works too, if you already have one set up.

### 2. Get Figma access connected

Our plugins read designs straight from Figma, so if you're doing any Figma-to-code work, make sure your Figma Dev Mode MCP connection is set up in Claude Desktop before you try to use one of these skills — otherwise it won't be able to pull a design at all.

### 3. Install a plugin

In the **Code tab** of Claude Desktop, type:

```
/plugin marketplace add P4-Product-Design/<repo-name>
/plugin install <plugin-name>@<plugin-name>
```

Check the specific repo's README for its exact plugin/marketplace name — for example, the Figma-to-Shopify-Liquid plugin is:

```
/plugin marketplace add P4-Product-Design/figma-to-shopify-liquid
/plugin install figma-to-shopify-liquid@figma-to-shopify-liquid
```

Installed plugins show up under **Customize → Manage plugins** in the Code tab, where you can update or remove them later.

If step 1 wasn't done first, this will fail with a "marketplace not found" error — that's always a sign your machine isn't authenticated yet, not a permissions problem.

## Current repos

| Repo | What it does |
|---|---|
| [figma-to-shopify-liquid](https://github.com/P4-Product-Design/figma-to-shopify-liquid) | Converts a Figma design into a pixel-exact Shopify Liquid section/block, with matching docs and a static preview. |

## Questions

Message Chance.
