# P4-Product

Internal home for Swolverine's design-to-code tooling — Claude Code/Desktop plugins that turn Figma designs into production-ready code, plus other team automation as it gets built.

## Getting access

Our plugin repos are public, so **you don't need to join the org just to install and use a plugin** — skip straight to **Setup** below.

You only need an invite if you want to contribute — push a new skill, fix something in an existing one, or create a new repo here. If that's you, message Chance with your GitHub username for an org invite (you'll get an email link to accept, good for 7 days).

## Setup (do this once)

**Never used GitHub before? You don't need to learn it.** Two ways to install a plugin — pick whichever feels easier.

### Option A: point-and-click (recommended if you're not sure)

1. In Claude Desktop, click **Customize** in the sidebar.
2. Next to **Personal plugins**, click **+** → **Add** → **Add marketplace**.
3. Paste `P4-Product-Design/figma-to-shopify-liquid` into the URL field and click **Sync**.
4. This only adds the marketplace — it doesn't install the plugin yet. Click **Plugins** in the Customize sidebar to open the Directory, find the `figma-to-shopify-liquid` tab, and click the **+** on its card to actually install it.

### Option B: type it in the Code tab

Look at the top of the Claude Desktop window — there are three tabs: **Chat**, **Cowork**, **Code**. This only works in **Code** (typing it elsewhere gives a "not available in this environment" error — that just means you're in the wrong tab). In the Code tab, type:

```
/plugin marketplace add P4-Product-Design/figma-to-shopify-liquid
/plugin install figma-to-shopify-liquid@figma-to-shopify-liquid
```

Either way, it shows up under **Customize → Manage plugins** afterward, where you can update or remove it. For future repos added here, swap in that repo's name — check its own README to confirm the exact plugin name.

### Also worth doing: connect Figma

Our plugins read designs straight from Figma. If you're doing Figma-to-code work, paste this into any Claude Desktop tab:

> Help me connect my Figma account to Claude Desktop so design skills can read Figma files. Walk me through it step by step.

### Stuck?

Paste this in wherever you got stuck:

> I'm trying to install a Claude plugin called figma-to-shopify-liquid from the P4-Product-Design GitHub org and it's not working. Help me figure out why and fix it.

## Current repos

| Repo | What it does |
|---|---|
| [figma-to-shopify-liquid](https://github.com/P4-Product-Design/figma-to-shopify-liquid) | Converts a Figma design into a pixel-exact Shopify Liquid section/block, with matching docs and a static preview. |
| [dev-handoff](https://github.com/P4-Product-Design/dev-handoff) | Turns a Figma design into an engineer-ready handoff — Requirements and Dev Spec frames plus native Dev Mode breakpoint annotations written back into the file. |
| [figma-to-optimizely](https://github.com/P4-Product-Design/figma-to-optimizely-plugin) | Turns a Figma design into production-ready Optimizely Web Experiment widgets (HTML, CSS, JS, widget.json) with a local preview server. |
| [product-block-gatherer](https://github.com/P4-Product-Design/product-block-gatherer) | Gathers and fills product block data for Fortune Shop and NCOA Shop pages, outputting a Product Block Lite and Foundational Product Block as a Word document. |
| [qual-research-simulator](https://github.com/P4-Product-Design/qual-research-simulator) | Simulates qualitative user research sessions against a Figma design using data-grounded personas that react independently, like real participants in a usability study. |
| [swolverine-product-photos](https://github.com/P4-Product-Design/swolverine-product-photos) | Turns raw Swolverine studio shots into website-ready product images — a cut-out on a transparent canvas with the house tone curve and a faint reflection, no generative fill. Needs a Mac with Photoshop 2026. |

## Questions

Message Chance.
