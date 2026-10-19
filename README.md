# MindSeries brand art

Channel banners (2560x1440) and profile pictures (800x800) for the
100 personal-development channels (ids 5..104), rendered from
`projects/multichan/make_brand.py`.

The factory's `set_brand.py` sets each channel's banner on YouTube by
pulling `https://raw.githubusercontent.com/Fyosamu/brands/main/<id>_banner.jpg`
- that is why this repo exists: the YouTube API wants a public image URL.
