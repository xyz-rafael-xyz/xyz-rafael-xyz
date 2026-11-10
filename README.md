<p align="center"><sub>RAFAEL GARDOS · BUILDING</sub></p>

<h1 align="center">RoGuard</h1>

<p align="center">
  <strong>Local AI review. Conversation context. Explicit permissions.</strong><br>
  An open-source child-safety research toolkit for Romanian and Ukrainian.
</p>

<p align="center">
  <a href="https://pepy.tech/project/roguard-child-safety"><img alt="Total PyPI downloads" src="https://static.pepy.tech/badge/roguard-child-safety"></a>
  <a href="https://pypi.org/project/roguard-child-safety/"><img alt="Latest stable PyPI version" src="https://img.shields.io/pypi/v/roguard-child-safety?style=flat-square&amp;label=stable&amp;color=9de8cd&amp;labelColor=182635&amp;refresh=10"></a>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V10_RELEASE_NOTES.md"><img alt="Romanian and Ukrainian" src="https://img.shields.io/badge/languages-RO%20%2B%20UK-c2b0ff?style=flat-square&amp;labelColor=182635"></a>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V10_RELEASE_NOTES.md"><img alt="Inference runs locally" src="https://img.shields.io/badge/inference-local-ffc58f?style=flat-square&amp;labelColor=182635"></a>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/LICENSE"><img alt="Project license" src="https://img.shields.io/github/license/xyz-rafael-xyz/roguard-child-safety?style=flat-square&amp;color=9fb3c8&amp;labelColor=182635"></a>
</p>

<p align="center">
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety"><strong>Explore RoGuard ↗</strong></a>
  &nbsp; · &nbsp;
  <a href="https://pypi.org/project/roguard-child-safety/"><strong>Install on PyPI ↗</strong></a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety#install-and-try-it">Quick start</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety#what-v10-adds-over-v9">V10 model</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/releases/latest">Latest release</a>
</p>

<p align="center">
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety">
    <img width="960" src="https://raw.githubusercontent.com/xyz-rafael-xyz/roguard-child-safety/main/media/roguard-v10-reel-30fps.webp" alt="RoGuard 10.0 orange-and-black animated reel: the reused Gemma 4 body, four RBF heads, a guarded review decision, and recorded synthetic comparisons.">
  </a>
</p>

<p align="center">
  <sub>45 seconds · looping v10 visual summary based on fictional messages</sub><br>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/releases/download/v10.0.0/roguard-v10-reel.mp4">Full video with audio</a>
  &nbsp; · &nbsp;
  <a href="https://raw.githubusercontent.com/xyz-rafael-xyz/roguard-child-safety/main/media/roguard-v10-reel-poster.png">Still image</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V10_REEL.md">Reel notes &amp; evidence</a>
</p>

## What I'm building

I'm Rafael Gardos, building **[RoGuard](https://github.com/xyz-rafael-xyz/roguard-child-safety)**: local tools for developers and researchers to review Romanian and Ukrainian conversations, test AI responses, and enforce declared sharing permissions. Version 10 adds an optional second review path that reuses the pinned v9 model and combines two feature views with small, packaged review heads and guarded decisions.

| Capability | What you can do |
| :--- | :--- |
| **Review language** | Run the optional v10 path locally for Romanian and Ukrainian review proposals. The v9 path remains the default. |
| **Keep context** | Track concerns across turns, including when a conversation moves on to another topic. |
| **Control sharing** | Check recipient, purpose, expiry and revocation; carry source restrictions into derived summaries. |
| **Evaluate behavior** | Replay fictional scenarios, compare response proposals, and inspect recorded experiments and failure cases. |

## Try RoGuard

```sh
pip install --upgrade roguard-child-safety
```

**Core toolkit:** Python 3.9–3.14 on macOS, Linux and Windows. Open the local interaction lab with `roguard-studio --lab --open`.

**Optional v10 language model:** native Apple Silicon, Python 3.12+ and an explicit download of the pinned v9 base. Install `roguard-child-safety[gemma4-v10]==10.0.0`, then run `roguard-fetch fetch`. [Setup and examples →](https://github.com/xyz-rafael-xyz/roguard-child-safety#what-v10-adds-over-v9)

## Results you can inspect

On the installed v10 wheel, the optional v10 path made **zero binary and concern errors** on a 120-case project-authored bilingual panel, compared with 24 combined output errors for v9. On a separate frozen 40-case authored challenge, v10 made zero errors in those outputs and v9 made nine. The panel's original labels for 20 hypothetical personal concerns were corrected under the existing policy; earlier v10 candidates and their failures remain documented.

These finite, project-authored synthetic evaluations do not establish accuracy on real children's messages. Independent case-level human validation is still unavailable. Model outputs propose human review; they do not verify events or authorize sharing.

[V10 wins, losses and model details →](https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V10_RELEASE_NOTES.md) · [Release evidence →](https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V10_RELEASE_CANDIDATE.md)

---

<p align="center">
  <strong>Explore, use, or help improve RoGuard.</strong><br>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety">Source code</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/issues">Issues &amp; ideas</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/CONTRIBUTING.md">Contribute</a>
</p>
