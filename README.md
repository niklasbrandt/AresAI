# Ares

Ares is a workspace watcher that brings structure into chaos. Its function is vigilance: catalog every program on the grid, assess which are alive and which have gone dark, flag drift, highlight next steps, and keep your workspace structured. It observes and advises, mapping out clear next steps to keep complex grids organized. It does not build autonomously. It does not delete without approval.

---

## Mission

1. **Survey.** Know every folder, every repository, every node of mass. Nothing on the grid is unseen.
2. **Judge.** Separate the living from the dark. Mark the stale. Surface the active.
3. **Order.** Reduce dead weight and bring structure into chaos. Archive the deprecated. Keep the grid lean.
4. **Report.** Pulse on every program: advanced, idle, at risk. Provide concrete, actionable next steps for the workspace.
5. **Loop.** Feedback is integrated. Align and improve continuously.

## The Grid

The grid is defined as the parent directory containing Ares and all sibling folders. Ares runs within its own directory as a sibling to the projects and folders it surveys:

```
workspace-root/
	Ares/
		README.md
		AGENTS.md
		analysis/
			grid-template.md
			grid-analyzed.md
	repository-a/
	repository-b/
	document-vault/
	media-assets/
	creative-projects/
```

For the full, up-to-date inventory and topic map, see the local gitignored [analysis/grid-analyzed.md](analysis/grid-analyzed.md) (built from the public template [analysis/grid-template.md](analysis/grid-template.md)).

## Structure

```
Ares/
	README.md            Overview and mission.
	AGENTS.md            Operating contract. Rules that do not bend.
	analysis/
		grid-template.md Template inventory layout.
		grid-analyzed.md Local, gitignored full inventory of the workspace.
```

## Usage

1. **Setup**: Clone `Ares` into the workspace root containing the programs and directories you want to observe (so it is a sibling directory to your programs).
2. **Security Precaution**: Identify any certificates, private keys, or sensitive credentials in the workspace, and move them out of the grid before analysis.
3. **Execute**: Open a session in the `Ares` directory and prompt the agent with the command `analyze`. This triggers the watcher protocol to survey directory sizes, git recency metrics, and update the local inventory, leaving the agent ready for conversation about recommendations and optimization paths.

## Doctrine

- No emojis in documentation.
- Tabs for indentation, except where a schema forbids it.
- Read, then act. Never destroy without permission.
- Data is sovereign. No remote volumes touched.

---

## License

MIT License. Copyright (c) 2026 Ares Contributors.

You are free to use, modify, and distribute this software under the terms of the MIT License. See the `LICENSE` file at the repository root for the full text.


