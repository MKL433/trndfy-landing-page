# Instagram Carousel 01

## Concept

**Hook:** Your song needs a campaign, not posts.

This carousel translates the current TRNDFY landing page positioning into a cleaner feed post: premium, data-driven campaign operations for artists, labels, and distributors. The layout is intentionally minimal, with one idea per slide, large safe margins, high-contrast typography, and very few decorative elements.

## Exported Slides

- `exports/slide-01.png` — cover / positioning
- `exports/slide-02.png` — problem framing
- `exports/slide-03.png` — campaign planning framework
- `exports/slide-04.png` — platform mix
- `exports/slide-05.png` — CTA

All exports are `1080x1350` PNG files.

## Caption

A release does not grow because it gets uploaded everywhere. It grows when the hook, audience, platform, creative, and reporting all work from one plan.

TRNDFY builds paid social campaigns for artists, labels, and distributors across Meta, TikTok, Instagram, and YouTube — with weekly reporting and daily artist-data reads.

If you’re planning a serious release campaign, send us the record.

DM `CAMPAIGN` or email `ads@trndfy.com`.

## Export Command

From the repository root:

```bash
for i in 1 2 3 4 5; do
  google-chrome --headless=new --no-sandbox --disable-gpu --hide-scrollbars \
    --window-size=1080,1350 \
    --screenshot="social/post-01-carousel/exports/slide-0${i}.png" \
    "file://$PWD/social/post-01-carousel/index.html?slide=${i}"
done
```

