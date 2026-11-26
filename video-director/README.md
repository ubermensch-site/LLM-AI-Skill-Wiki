# video-director

A code-first video-direction skill for Claude Code and other capable coding agents. It turns a brief into a deterministic HTML, Canvas, SVG, Three.js, GSAP, or Remotion film rendered frame by frame to MP4, covering launch films, promos, explainers, kinetic type, data stories, character shorts, loops, and social reels.

## Why it is trusted

- MIT-licensed and maintained as a real software project, not a prompt-only collection.
- Includes a methodology document, templates, references, automated timeline validation, video QA, tests, and CI.
- Uses explicit quality gates for timing, readability, safe areas, transitions, sound, loudness, and independent review.
- Publishes evaluation results while clearly noting their limited, non-controlled nature.

## Highlights

- A seven-phase-plus-review workflow from treatment to delivery.
- Deterministic, seekable animation contracts driven by a single timeline.
- Craft references for pacing, sound, typography, motion, camera, and visual continuity.
- `check_timeline.py` and `qa_video.py` for measurable pre-render and post-render checks.

## Install

Clone the repository and copy the inner skill folder into Claude Code's personal skills directory:

```bash
git clone https://github.com/win4r/video-director.git
cp -R video-director/video-director ~/.claude/skills/
```

The scripts use Python 3 with NumPy and Pillow; rendering requires FFmpeg/FFprobe and a browser or Remotion setup.

## Source

[win4r/video-director](https://github.com/win4r/video-director)
