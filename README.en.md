<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 039 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 039

### Keep one photograph's essence in one living field of Chinese silk

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-D83D55?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-2A7B80?style=flat-square)](#)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> ONE IMAGE · ONE ESSENCE · SILK DIRECTION · CLEAN GROUND · EASTERN SILENCE

One posture, contour, relation, action, or symbolic detail carries the whole source through layered Chinese silk, varied stitch direction, luminous colour, unfinished edges, and active Eastern whitespace.

## Why this Skill exists

The style is source-dependent, not a decorative preset. Its operative transformation is:

```text
understand the source's one true core → choose one representative image → preserve three recognition cues → translate form into varied Chinese silk stitches → alternate dense embroidery with a few lines and unfinished contour → derive luminous thread colour from the source → use clean silk ground as air and aftertaste → add one light editorial phrase
```

If an unrelated photograph could replace the source without materially changing recognition, construction, placement, material, colour, whitespace, and copy, the result does not belong to this Panel.

## The visual contract

- One image carries one meaning. Do not embroider the whole photograph or convert every visible object.
- Preserve at least three source cues in one posture, contour, relation, action, or symbolic detail.
- Use authentic flat stitch, long-and-short stitch, couching, wrapped thread, seed stitch, and laid thread as appropriate; vary direction, density, layering, and sheen with the form.
- Let embroidery and non-embroidery compose together: some areas may be precise, others only a few stitches, a free thread, or an unfinished boundary.
- Choose a clean white, cool white, ivory, pale-colour, or source-earned pure coloured silk ground; never default to dirty beige, yellowed linen, stains, or faux ageing.
- Build lively source-derived thread steps through close hues, small complements, tiny high-purity accents, and directional shimmer; rich but not chaotic, bright but not vulgar.

Complete aesthetic constraints and rejection rules live in the Skill and production prompts. They preserve the original brief without turning its historical 3:4 canvas into a hidden default. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-039-prompt.en.md)

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2090817611953270966) · 2026-08-21<br>
> GPT2 x 刺绣 x 内核 x 美学提示词 x VOL.039

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090817611953270966"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 039 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090817611953270966"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 039 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2090817611953270966"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 039 sample 3"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2090817611953270966">View the original post and full prompt →</a></p>

These samples demonstrate the 039 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 039 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 039 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 039 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy and locale

Automatic copy, exact custom copy, or text-free output is confirmed before generation. Copy follows the intended audience rather than the command language, and exact user wording remains verbatim.

Project-specific copy rule: Use one very short word or phrase distilled from unspoken emotion, action, relation, or implication. Render it as fine native thread, a slender title slip, or minimal editorial type that follows a free strand, enters negative space, or rests beside the embroidered edge.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-039.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-039" ~/.codex/skills/xxd-panel-039
```

Claude Code users may link the same folder under `~/.claude/skills/xxd-panel-039`. Restart the agent session after installation.

```text
$xxd-panel-039
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

Full specifications: [Skill workflow](SKILL.md) · [source archive](references/039-source.md) · [English prompt](references/xxd-panel-039-prompt.en.md) · [Chinese prompt](references/xxd-panel-039-prompt.zh-CN.md)

## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

### In-depth consultation · CNY 299/hour

One-to-one in-depth consultation for using Skills. Contact Xiaoxiaodong through WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills User Community · CNY 99

A one-time fee joins the Skills user community for workflow sharing and peer discussion; hourly consultation is separate.

### Knowledge Planet + Member Prompt Library · CNY 699/year

One annual payment opens both Knowledge Planet and the member prompt library. Join either side, then contact Xiaoxiaodong on WeChat for the other access.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>Embroider only what deserves to remain; let everything else become breath.</strong></div>

---

<div align="center">

## Support this open-source project

Chinese-language support may use Xiaoxiaodong's own WeChat or Alipay reward codes; other editions use Buy Me a Coffee. Support is optional and never changes access to the open-source project.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
