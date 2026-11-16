# spellcache-data

Live stock and price data for [Spellcache](https://spellcache.netlify.app), a Singapore-only
Magic: The Gathering singles binder.

`stock.json` is rebuilt every morning (Singapore time) from Card Kingdom prices and the
current stock, and loaded by the site when it opens. It holds only what the site already
shows publicly: card names, sets, quantities and prices.
