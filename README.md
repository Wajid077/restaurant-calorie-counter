# Restaurant calorie counter

A small, dependency-free calorie counter for restaurant meals. Tap + on the dishes you're ordering and it adds up calories, protein and salt. Calories are shown against the 2,000 kcal adult reference and salt against the NHS limit of 6g a day.

**Live:** https://wajid077.github.io/restaurant-calorie-counter/

## Embed it

```html
<iframe src="https://wajid077.github.io/restaurant-calorie-counter/?embed" title="Restaurant calorie counter" width="100%" height="620" style="border:0;max-width:760px" loading="lazy"></iframe>
```

Adding `?embed` hides the intro and footer so it fits neatly in a sidebar or article.

## Data

The current dataset covers 69 mains, sides and lunch dishes from the Wagamama UK menu (November 2026), taken from the restaurant's published nutrition information. The full table, including desserts, drinks, carbs, sugar and fat, is at [WagamamasMenu.uk](https://wagamamasmenu.uk/menu/calories/).

Figures change when recipes do, so treat them as a guide rather than medical advice. This is an independent project and isn't affiliated with any restaurant brand.

## How it's built

One HTML file of about 12 KB with inline CSS and JS. It has no framework, makes no network requests and uses no cookies, so it loads instantly and adds nothing to your page's Core Web Vitals when lazy-loaded in a frame.

MIT licence.
