# oneprompt1story-breaktest
#Break-testing 1Prompt1Story: ID vs OOD (Hinglish)

This repo:
1) Uses the upstream **1Prompt1Story** benchmark (ConsiStory+) as **ID** baseline.
2) Runs a new **Hinglish Story Set (60)** as **OOD** using the same seeds/hparams.
3) Evaluates both with CLIP metrics (CLIP-T↑, CLIP-I↑) and reports the **twist** (ID→OOD shift).

## Setup

```bash
bash scripts/00_setup.sh
