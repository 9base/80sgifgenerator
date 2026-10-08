> [!NOTE]
> **9base status: Preserved.** Lifecycle: archived reference; not actively maintained by 9base.
>
> JavaScript/GLSL animated-text GIF generator, retained from [antoineMoPa/80sgifgenerator](https://github.com/antoineMoPa/80sgifgenerator). The source project and its original contributors retain their attribution; this repository is a preserved fork.
>
> The audited `master` and `gh-pages` heads matched the same-named upstream heads. No 9base-specific technical development was established.
>
> Retained here for reference and preservation. The original reason for retaining this copy is undocumented; no larger 9base project family was established.
>
> Archival context reconstructed on 8 October 2026 from the repository, branch history and GitHub fork metadata; it does not imply new technical work.

---

<!-- Original upstream README follows unchanged. -->

# Animated gif generator

A gif generator coded in javascript & glsl.

The text is created with a hidden `<canvas>` element. It is then stored in a texture and color coded by the text position (top = r / middle = g / bottom=b). This texture is used to create nice text effects.

# Modes

Try them: https://antoinemopa.github.io/80sgifgenerator/

## 80's

![Example](http://67.media.tumblr.com/2a9c4960d1f491d018d76e85e723dd6e/tumblr_ofts9tdjNK1svno9go1_540.gif)

## 80's + vhs

![Example](http://i.giphy.com/l3vRl4kzQVUJxu9ws.gif)

## 2001

![Example](http://67.media.tumblr.com/50021751fd756edefef0a01f6f46dcba/tumblr_ofwculkEOD1svno9go1_540.gif)

# Want to code things like this?

Start with shadergif http://a-mo-pa.com/stuff/shadergif/
