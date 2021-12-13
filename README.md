# Firefox Theme uberAgent ESA

A theme based on the color scheme of [uberAgent ESA](https://uberagent.com/). The toolbar color has been chosen in such a way that the browser does NOT auto-select dark mode for websites.

## Notes

### Theme Color and Dark Mode

Firefox switches to dark mode automatically depending on the toolbar color of the browser theme. Firefox chooses dark mode independent of the related OS setting.

### Header Image and Text Shadow

When a theme contains a header image (manifest setting `theme_frame`), the active tab's text gets a shadow, which makes it harder to read and generally does not look great. As of Firefox 95 there is no way to disable the text shadow except by _not_ specifying `theme_frame`. That is the reason why this theme does not have a header image.
