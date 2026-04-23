# Add the Activity Finder widget to your website

Follow these steps to show the Activity Finder search on your site. If someone else manages your website, send them this page or ask them to add the code for you.

**Live example:** [see the widget on a minimal demo page](https://teamplayed.github.io/af-widget/example.html) (same script URL and optional attributes as below).

## 1. Add the script

Open your site’s settings where you can edit the HTML, or ask your web person to do this.

**Option A — Always get the newest version**

The widget will update automatically when Activity Finder releases improvements. Use this if you are comfortable with occasional small changes.

```html
<script async src="https://widget.activityfinder.net/app.js"></script>
```

**Option B — Keep one fixed version (often better for busy sites)**

The widget stays the same until you change the link. After you have tested a version and are happy with it, use a link like the one below. Replace `v2.0.0` with the version your team or Activity Finder has asked you to use.

```html
<script async src="https://widget.activityfinder.net/releases/v2.0.0/app.js"></script>
```

Place this script in the `<head>` section of your page, or wherever your website builder or theme expects “header” or “before closing head” scripts.

## 2. Add the widget on the page

Put this line where you want the search box and results to appear (for example in the main content area of a page):

```html
<played-activity-widget></played-activity-widget>
```

Save and publish. The widget should load on that page after a refresh.

## Optional: customize the look and text

You can add attributes to the `<played-activity-widget>` tag to match your branding. Use your normal text and colour tools; hex colours look like `#23d3a6`.

| What you can change | What it does | Example |
| ------------------- | ------------ | ------- |
| `sub-domain` | Which Activity Finder site visitors are sent to | `played` |
| `canvas-colour` | Background colour behind the widget | `#23d3a6` |
| `font` | Font for the widget text | `Arial` |
| `main-title` | Large heading above the search | `Get Active` |
| `sub-title` | Smaller line under the heading | `Search for activities` |
| `primary-color` | Colour for buttons and icons | `#2341bc` |

Example with options:

```html
<played-activity-widget
  main-title="Get Active"
  sub-title="Search for activities near you"
  primary-color="#2341bc"
></played-activity-widget>
```

## Support

For help with embedding the widget, choosing a version, or troubleshooting (for example the widget not appearing on your site), email **[team@played.co](mailto:team@played.co)**.
