<p align="center"><sub>RAFAEL GARDOS · BUILDING</sub></p>

<h1 align="center">RoGuard</h1>

<p align="center">
  <strong>Local AI review. Conversation context. Explicit permissions.</strong><br>
  An open-source child-safety research toolkit for Romanian and Ukrainian.
</p>

<p align="center">
  <a href="https://pepy.tech/project/roguard-child-safety"><img alt="Total PyPI downloads" src="https://static.pepy.tech/badge/roguard-child-safety"></a>
  <a href="https://pypi.org/project/roguard-child-safety/"><img alt="Latest stable PyPI version" src="https://img.shields.io/pypi/v/roguard-child-safety?style=flat-square&amp;label=stable&amp;color=9de8cd&amp;labelColor=182635"></a>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V9_MODEL.md"><img alt="Romanian and Ukrainian" src="https://img.shields.io/badge/languages-RO%20%2B%20UK-c2b0ff?style=flat-square&amp;labelColor=182635"></a>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V9_MODEL.md"><img alt="Inference runs locally" src="https://img.shields.io/badge/inference-local-ffc58f?style=flat-square&amp;labelColor=182635"></a>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/LICENSE"><img alt="Project license" src="https://img.shields.io/github/license/xyz-rafael-xyz/roguard-child-safety?style=flat-square&amp;color=9fb3c8&amp;labelColor=182635"></a>
</p>

<p align="center">
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety"><strong>Explore RoGuard ↗</strong></a>
  &nbsp; · &nbsp;
  <a href="https://pypi.org/project/roguard-child-safety/"><strong>Install on PyPI ↗</strong></a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety#install-and-try-it">Quick start</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V9_MODEL.md">Model &amp; API</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/releases/latest">Latest release</a>
</p>

<p align="center">
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety">
    <img width="960" src="https://raw.githubusercontent.com/xyz-rafael-xyz/roguard-child-safety/main/media/roguard-v9-demo-loop.gif" alt="RoGuard 9.0 animated walkthrough: Romanian and Ukrainian review proposals, conversation context, permission revocation, and held-out synthetic evaluation.">
  </a>
</p>

<p align="center">
  <sub>28 seconds · illustrated workflows using actual v9 outputs and fictional messages</sub><br>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/releases/download/v9.0.0/roguard-v9-demo.mp4">Video with playback controls</a>
  &nbsp; · &nbsp;
  <a href="https://raw.githubusercontent.com/xyz-rafael-xyz/roguard-child-safety/main/media/roguard-v9-poster.png">Still image</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/DEMO_VIDEO.md">Transcript</a>
</p>

## What I'm building

I'm Rafael Gardos, building **[RoGuard](https://github.com/xyz-rafael-xyz/roguard-child-safety)**: tools for developers and researchers to review Romanian and Ukrainian conversations, test AI responses, and enforce declared sharing permissions.

| Capability | What you can do |
| :--- | :--- |
| **Review language** | Run the optional v9 model locally to propose messages for human review in Romanian and Ukrainian. |
| **Keep context** | Track concerns across turns, including when a conversation moves on to another topic. |
| **Control sharing** | Check recipient, purpose, expiry and revocation; carry source restrictions into derived summaries. |
| **Evaluate behavior** | Replay fictional scenarios, compare response proposals, and inspect recorded experiments and failure cases. |

## Try RoGuard

```sh
pip install --upgrade roguard-child-safety
```

**Core toolkit:** Python 3.9–3.14 on macOS, Linux and Windows. Open the local interaction lab with `roguard-studio --lab --open`.

**Optional v9 language model:** native Apple Silicon, Python 3.12+ and an explicit model download. [Setup and Python examples →](https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V9_MODEL.md)

## Results you can inspect

The v9 model classified **600/600 held-out synthetic cases correctly**, split equally between Romanian and Ukrainian. A separate 5,022-case regression evaluation recorded zero missed concerns and two Romanian false alerts.

These are project-authored synthetic evaluations; they do not establish accuracy on real children's messages. Model outputs propose human review. They do not verify events or authorize sharing.

[Evaluation and release evidence →](https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/docs/V9_STABILIZATION.md)

---

<p align="center">
  <strong>Explore, use, or help improve RoGuard.</strong><br>
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety">Source code</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/issues">Issues &amp; ideas</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/xyz-rafael-xyz/roguard-child-safety/blob/main/CONTRIBUTING.md">Contribute</a>
</p>
