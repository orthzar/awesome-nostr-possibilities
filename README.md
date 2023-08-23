# Awesome Nostr Possibilities
This repo contains a curated list of non-social-media use-cases for Nostr.

Nostr presents an incredible opportunity to re-revolutionize how we use the internet, the previous revolution being the web browser. But Nostr will never do that if everyone stays focused on using it as Yet Another Social-media Protocol (YASP). If Nostr never transcends social-media, it will fade into obscurity, just like [Usenet](https://en.wikipedia.org/wiki/Usenet), the original social media.

Feel free to create an issue if...
- you have an idea that you think should be added to this list; or
- you have a link to an implementation of an idea in this list;

... I'll consider adding it to the list.

Also, check out this related repo: https://github.com/aljazceru/awesome-nostr

## The List

- A ridesharing app. (e.g. the incomplete [bullrun](https://github.com/ArcadeCity/bullrun))
- CoinJoin negotiation. (e.g. [joinstr](https://github.com/22388o/joinstr))
- An end-to-end encrypted messaging app, like [Signal](https://github.com/signalapp/libsignal), that uses Nostr for the backend.
  - Consider using something like SimpleX Chat's [identity-less system](https://github.com/simplex-chat/simplex-chat), instead of npubs.
- Comand-and-control, for controlling your machines via a local Nostr relay.
- A bracketing/tournament system with payouts. (see [here](https://stacker.news/items/226921) for details)
- Matchmaking for videogames, where clients/servers submit offers via Nostr to start/host game matches.
- To replace videogame servers, by sending game-state updates between clients via one or more relays. Multiple relays might be appropriate for redundancy.
- Webpages, where each webpage is stored across multiple relays, making them virtually uncensorable.
