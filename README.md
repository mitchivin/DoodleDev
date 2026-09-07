# DoodleDev

A visual design tool for the web. Draw on the canvas and export production HTML, CSS, and JavaScript as a standalone page or Web Component, with no runtime dependencies.

[doodledev.app](https://doodledev.app)

<p align="center">
<img width="1920" height="1080" alt="doodledev-editor" src="https://github.com/user-attachments/assets/3bfeed1d-a714-4e20-a25a-bcf140ea4c8c" />
</p>

## Features

- Vector canvas with shapes, pen / bezier paths, text, images, groups, and a boolean shape builder
- Styling covers fills, strokes, gradients, shadows, glow, lighting, blur, and noise
- Infinite canvas, layers, grouping, and local `.doodle` File Open / Save
- Welcome presets for Mi Boy Color and MiPod Classic
- Export as a Web Component or a full HTML page, with an optional ZIP when the design includes image assets
- Exported output stands alone. No React, Vue, or other runtime library required

<p align="center">
<img width="1920" height="1080" alt="doodledev-export" src="https://github.com/user-attachments/assets/63b877a5-b963-4a44-8344-3db2bfb63ea5" />
</p>

## Export

Drop the export into any site and use the custom element (default tag / file name):

```html
<script type="module" src="./doodledev-export.js"></script>

<doodledev-export></doodledev-export>
```

The widget id (and therefore the tag and filename) can be customized at export time.

## Stack

- Vanilla HTML / CSS / JavaScript
- Paper.js for boolean shape operations
- Cloudflare Worker for heavier export processing. Final DOM assembly is in the browser.

## Related

Shells designed in DoodleDev:

- [Mi Boy Color](https://builds.doodledev.app/#/miboy) - Game Boy Color style handheld shell
- [MiPod Classic](https://builds.doodledev.app/#/mipod) - iPod Classic style click-wheel shell
- [MitchIvin XP](https://mitchivin.com/) - Windows XP portfolio desktop

## Credits

Built by [Mitch Ivin](https://mitchivin.com/).

## License

Source stays private.
