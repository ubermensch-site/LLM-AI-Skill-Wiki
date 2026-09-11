# dream-loop

**What it is:** A build loop for *high-fidelity visuals* where the agent first generates a “dream” target screenshot, then iterates on the code until a critic model judges the live screenshot matches the target.

**Why it’s worth including:**
- Clear, scoped SKILL.md with a repeatable workflow (dream → build → critique → iterate).
- MIT-licensed and already has strong community traction for a newly created repo.
- Practical for modern coding-agent harnesses that support vision + optional subagents.

**Source:** https://github.com/achimala/dream-loop

## Notes

- Requires an agent that can generate images (built-in or via API) and can take screenshots / do visual comparison.
- Primarily targeted at 3D scenes (e.g., Three.js + optional Blender), but can be used for any UI/app with strong visual requirements.
