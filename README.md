# FeruOTS media

Promotional material for [FeruOTS](https://www.feruots.eu): animated banners that streamers can put over their gameplay.

**Preview of every format: [feruots.eu/stream-banner](https://feruots.eu/stream-banner).**
**Downloads are on the [Releases](https://github.com/servant777servant/feruots-media/releases) page.** The newest release is always on top.

## Adding the banner to OBS

1. Download the `.webm` file from the newest release. It has a transparent background.
2. In OBS: **Sources → + → Media Source**, name it for example "FeruOTS banner".
3. Choose the downloaded file as **Local File** and tick **Loop**.
4. Move and resize it while holding **Shift**. For a sharper result when scaling down: right-click the source → **Scale Filtering → Lanczos**.

If your software does not show the transparency (some Streamlabs versions), use the `.mp4` file instead. It is the same banner on a black background.

## What is in this repository

- `banner/` holds the previews used by the stream banner page (served through GitHub Pages): animated AVIF files, a poster and still images. The full-size files are only in Releases.
