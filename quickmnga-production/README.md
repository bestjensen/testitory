# QuickMNGA Production Workspace

Shared planning and production scaffold for QuickMNGA Shorts and future long-form manga/manhwa recap work.

## Repository layout

```text
quickmnga-production/
├── AGENTS.md                    # Codex operating rules for this workspace
├── README.md
├── docs/
│   ├── WORKFLOW_SHORTS.md
│   ├── WORKFLOW_LONGFORM.md
│   ├── STYLE_GUIDE.md
│   └── SOURCE_AND_RIGHTS.md
├── data/
│   ├── source_videos.csv        # Long recap/reference videos
│   ├── clip_bank.csv            # Candidate Short scenes + timestamps + hooks
│   ├── manga_sources.csv        # Chapter/official-source mapping
│   └── asset_registry.csv       # Memes, reactions, SFX, music, branding
├── templates/
│   ├── short_project.yaml
│   ├── longform_project.yaml
│   └── asset_manifest.yaml
├── projects/
│   ├── shorts/                  # One folder per Short
│   └── longform/                # One folder per long recap
├── transcripts/                 # Our transcripts/notes; see rights policy
├── scripts/                     # Approved QuickMNGA scripts
└── assets/
    ├── branding/
    ├── manga/
    ├── memes/
    ├── reactions/
    ├── sfx/
    └── music/
```

GitHub does not preserve empty directories, so folders that primarily hold media are represented by README or manifest files until assets are added.

## Storage model

This repository is currently public. Keep copyrighted/licensed media binaries out of it. Use it for manifests, scripts, notes, source URLs, timestamps, project configs and Codex code. When a private media repository or shared media store is created, the manifests can point to those files.

## Core idea

1. Mine long recap videos for strong self-contained scenes.
2. Map each scene to the underlying manga/manhwa chapter/pages.
3. Write an original QuickMNGA script in the chosen narrator style.
4. Build a 9:16 edit from authorized/user-provided panels plus original/licensed meme/reaction assets.
5. Render in Codex/Remotion.
6. Track analytics and feed what works back into the clip bank.

The same research, chapter mapping and transcript notes can later feed the long-form recap channel.
