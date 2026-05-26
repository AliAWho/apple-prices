# AppleSMP Market Trends
Incomplete. This **does** use AI, I'm not good at making pages!

Tags
----


This project supports per-item tags displayed next to each item. Available tags (apply manually in code):

- Limited Market — "This item has a limited market. It is controlled by very few people."
- Rare — "This item is rare. Its price will be higher for this reason."
- Limited — "This item is limited. There is a set amount of how many there can be, and it will be/is not obtainable naturally."
- Bad Deal — "This item is priced too high. The market reflects this is the price, but it is too high for what it should be, {betterPrice}."

Usage
-----

No UI is provided to edit tags. To add tags, edit the `PRICES` array in [index.html](index.html) and include a `tags` array on the item, e.g. `tags: ['rare','limited-market']`. For `Bad Deal` use `betterPrice: '5'` to populate the tooltip.

By default no tags are applied.
