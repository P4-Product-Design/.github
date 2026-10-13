# P4 Product Design

Claude plugins for the P4 Product Design team: Figma-to-code, dev handoff, research, content, and product photos. Every plugin lives in one repo, **[claude-plugins](https://github.com/P4-Product-Design/claude-plugins)**, and installs from one marketplace.

## Install (one time, per person)

You don't need a GitHub account or any GitHub knowledge.

1. In Claude Desktop, click **Customize** in the sidebar.
2. Next to **Personal plugins**, click **+** → **Add** → **Add marketplace**.
3. Paste `P4-Product-Design/claude-plugins` and click **Sync**.
4. Click **Plugins** in the Customize sidebar, open the **p4-product-design** tab, and click **+** on each plugin you want.

New versions arrive on their own. If you installed P4 plugins before October 2026, remove those old plugins and marketplaces in **Customize → Manage plugins** first. The [claude-plugins README](https://github.com/P4-Product-Design/claude-plugins#readme) has typed commands and troubleshooting.

## Plugins

| Plugin | What it does | Owner |
|---|---|---|
| [dev-handoff](https://github.com/P4-Product-Design/claude-plugins/tree/main/plugins/dev-handoff) | Turns a Figma design into an engineer-ready handoff, with spec frames and Dev Mode annotations. | Chance Chipman |
| [figma-to-optimizely](https://github.com/P4-Product-Design/claude-plugins/tree/main/plugins/figma-to-optimizely) | Turns a Figma design into an Optimizely Web Experiment widget with a local preview. | Andy Ramos |
| [figma-to-shopify-liquid](https://github.com/P4-Product-Design/claude-plugins/tree/main/plugins/figma-to-shopify-liquid) | Converts a Figma design into a pixel-exact Shopify Liquid section or block. | Chance Chipman |
| [p4-publisher](https://github.com/P4-Product-Design/claude-plugins/tree/main/plugins/p4-publisher) | Adds your plugin or skill to the marketplace, or publishes an update. | Chance Chipman |
| [product-block-gatherer](https://github.com/P4-Product-Design/claude-plugins/tree/main/plugins/product-block-gatherer) | Fills product block data for Fortune Shop and NCOA Shop pages as a Word document. | Audrey McGlynn |
| [qual-research-simulator](https://github.com/P4-Product-Design/claude-plugins/tree/main/plugins/qual-research-simulator) | Runs a Figma design past data-grounded personas, like a simulated usability study. | Audrey McGlynn |
| [swolverine-product-photos](https://github.com/P4-Product-Design/claude-plugins/tree/main/plugins/swolverine-product-photos) | Turns raw Swolverine studio shots into website-ready product images. | Chance Chipman |

**Connect Figma first** if you'll do Figma work. Paste this into any Claude Desktop tab:

> Help me connect my Figma account to Claude Desktop so design skills can read Figma files. Walk me through it step by step.

## Contribute a plugin or skill

Install **p4-publisher** and ask Claude in the Code tab: "publish my <skill> to the P4 marketplace." Manual steps and the rules are in [CONTRIBUTING.md](https://github.com/P4-Product-Design/claude-plugins/blob/main/CONTRIBUTING.md). To push, you need org membership. Message Chance with your GitHub username for an invite. It expires after 7 days.

## Stuck?

Paste this into Claude:

> I'm trying to install a plugin from the P4-Product-Design/claude-plugins marketplace in Claude Desktop and it's not working. Help me figure out why and fix it.

Or message Chance.
