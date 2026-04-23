# Played — GitHub Pages assets

Static, publicly accessible files for **Played** integrations: [OpenActive](https://www.openactive.io/) **activity concept collections** (JSON-LD) and documentation for embedding the Activity Finder widget.

**Live site:** [https://teamplayed.github.io](https://teamplayed.github.io)

## Activity concept collections

Collections group activities from the [OpenActive activity list](https://openactive.io/activity-list/) for search, discovery, and product UX—separate from the strict concept hierarchy. The same activity can appear in multiple collections.

Each file is served as JSON-LD with `@type: ConceptCollection`. Background and API usage are described in the [iMin activity concept collections documentation](https://docs.imin.co/platform-products/search/imin-events-api/concepts/activities-and-collections/activity-concept-collections).

More detail: [collections/README.md](collections/README.md).

### Collection URLs

Prefix the filename with:

`https://teamplayed.github.io/collections/`

Example:

[https://teamplayed.github.io/collections/aqua.jsonld](https://teamplayed.github.io/collections/aqua.jsonld)

### Published collections

| File | URL |
|------|-----|
| `aqua.jsonld` | […/collections/aqua.jsonld](https://teamplayed.github.io/collections/aqua.jsonld) |
| `cardio.jsonld` | […/collections/cardio.jsonld](https://teamplayed.github.io/collections/cardio.jsonld) |
| `cardioldnsport.jsonld` | […/collections/cardioldnsport.jsonld](https://teamplayed.github.io/collections/cardioldnsport.jsonld) |
| `extreme.jsonld` | […/collections/extreme.jsonld](https://teamplayed.github.io/collections/extreme.jsonld) |
| `flexibilityldnsport.jsonld` | […/collections/flexibilityldnsport.jsonld](https://teamplayed.github.io/collections/flexibilityldnsport.jsonld) |
| `hollistic.jsonld` | […/collections/hollistic.jsonld](https://teamplayed.github.io/collections/hollistic.jsonld) |
| `low-impact.jsonld` | […/collections/low-impact.jsonld](https://teamplayed.github.io/collections/low-impact.jsonld) |
| `olympics.jsonld` | […/collections/olympics.jsonld](https://teamplayed.github.io/collections/olympics.jsonld) |
| `outdoor.jsonld` | […/collections/outdoor.jsonld](https://teamplayed.github.io/collections/outdoor.jsonld) |
| `recommended.jsonld` | […/collections/recommended.jsonld](https://teamplayed.github.io/collections/recommended.jsonld) |
| `sporty.jsonld` | […/collections/sporty.jsonld](https://teamplayed.github.io/collections/sporty.jsonld) |
| `strengthldnsport.jsonld` | […/collections/strengthldnsport.jsonld](https://teamplayed.github.io/collections/strengthldnsport.jsonld) |
| `walking.jsonld` | […/collections/walking.jsonld](https://teamplayed.github.io/collections/walking.jsonld) |

## Activity Finder widget

Embed instructions, script tag, markup, and optional element attributes: [af-widget/install.md](af-widget/install.md).

## Contributing

Add or edit `.jsonld` files under `collections/` and push to the default branch; GitHub Pages will publish updates according to your repository settings.
