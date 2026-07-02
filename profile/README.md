# P4-Product-Design

Internal home for Swolverine's design-to-code tooling — Claude Code/Desktop plugins that turn Figma designs into production-ready code, plus other team automation as it gets built.

## Getting access

Repos here are private. To get in:

1. **Message Chance with your GitHub username** and ask for an invite to the org.
2. You'll get an email with an invite link — accept it (expires after 7 days, so ping again if it lapses).
3. Once you're in, follow **Setup** below. Everything past this point is self-service — you shouldn't need to ask anyone anything else to get running.

## Setup (do this once, after joining)

**Never used GitHub before? You don't need to learn it.** Open the **Code tab** in Claude Desktop and paste this in — Claude will check your computer, install anything missing, and walk you through each step:

> I'm a new teammate at P4-Product-Design getting set up for the first time. Please help me: (1) check whether I have git and the GitHub CLI installed, install whatever's missing, and log me into GitHub so my computer can access our private repos, (2) check whether I have Figma connected in Claude Desktop and walk me through connecting it if not, and (3) once both of those work, add P4-Product-Design/figma-to-shopify-liquid as a plugin marketplace and install the figma-to-shopify-liquid plugin. Walk me through one step at a time and confirm each one works before moving to the next.

That's it for most people. The breakdown below is for anyone who wants to understand what's happening, redo just one step, or got stuck partway through.

### 1. Authenticate git to GitHub on your machine

Being an org member isn't enough on its own — your computer separately needs a way to prove it's you when it fetches a private repo. If you want to do this on your own instead of the prompt above:

> Help me install the GitHub CLI if I don't have it, then log me into GitHub with it so my computer can access a private GitHub organization called P4-Product-Design.

(Under the hood this is `gh auth login` — fine to run yourself in a terminal if you're comfortable with that instead.)

### 2. Get Figma access connected

Our plugins read designs straight from Figma. If you're doing Figma-to-code work:

> Help me connect my Figma account to Claude Desktop so design skills can read Figma files. Walk me through it step by step.

### 3. Install a plugin

> Add P4-Product-Design/figma-to-shopify-liquid as a Claude plugin marketplace and install the figma-to-shopify-liquid plugin from it.

Or type the same thing as commands directly in the Code tab:

```
/plugin marketplace add P4-Product-Design/figma-to-shopify-liquid
/plugin install figma-to-shopify-liquid@figma-to-shopify-liquid
```

For future repos added here, swap the repo/plugin name — check that repo's own README for its exact name. Installed plugins show up under **Customize → Manage plugins** in the Code tab, where you can update or remove them later.

### Stuck?

If you get a "marketplace not found" error, that always means step 1 didn't happen yet — it's not a permissions problem. Paste this in:

> I'm trying to install a Claude plugin from a private GitHub org called P4-Product-Design and got a "marketplace not found" error. Help me figure out why and fix it.

## Current repos

| Repo | What it does |
|---|---|
| [figma-to-shopify-liquid](https://github.com/P4-Product-Design/figma-to-shopify-liquid) | Converts a Figma design into a pixel-exact Shopify Liquid section/block, with matching docs and a static preview. |

## Questions

Message Chance.
