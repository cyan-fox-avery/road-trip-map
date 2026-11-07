# Road Trip Map

An interactive map for Avery and Harley to plan a road trip across the
continental US: coloured pins by attraction type, click-through links, and a
sortable list page with descriptions, prices, visit times, seasons, and
reviews links.

- **Live site:** https://cyan-fox-avery.github.io/road-trip-map/
- **Built with:** Leaflet + OpenStreetMap, plain static HTML. No build step,
  no API keys, no server.
- **Data:** every attraction is an entry in the site's place list, added by
  hand and verified (address, coordinates, price tier, season, hours) before
  it goes on the map.

## Adding a place

Places are added one at a time: name, categories (a place can belong to more
than one — the first sets its pin colour), state, city/town, address,
website, short description, price tier (Free / $ / $$ / $$$), time it takes
(quick stop, 1–2 hours, half day, full day, multi day), seasons, star rating
(ours, 1–5, only after visiting), reviews link, status (want to go /
visited), notes, and an optional one-line must-see highlight. Coordinates
are looked up from the address.

## Places so far (31)

Dollywood (TN), Hersheypark (PA), Walt Disney World (FL), Portillo's Chicago
(IL), Dog Mountain (VT), International Cryptozoology Museum (Bangor, ME),
Mothman Museum (WV), House on the Rock (WI), City Museum (St. Louis, MO),
Meow Wolf House of Eternal Return (Santa Fe, NM), Very Large Array (NM),
Best Friends Animal Sanctuary (Kanab, UT), Museum of Make Believe (Laguna
Beach, CA), Madonna Inn (San Luis Obispo, CA), Piedras Blancas Elephant Seal
Rookery (San Simeon, CA), The Mystery Spot (Santa Cruz, CA), Musée Mécanique
(San Francisco, CA), The Wave Organ (San Francisco, CA), Confusion Hill
(Leggett, CA), Avenue of the Giants (Weott, CA), Salvation Mountain (Niland,
CA), Mothership (San Diego, CA), Corvette Diner (San Diego, CA), San Diego
Air & Space Museum (San Diego, CA), Disneyland Park (Anaheim, CA), Knott's
Berry Farm (Buena Park, CA), Medieval Times Buena Park (Buena Park, CA),
Aquarium of the Pacific (Long Beach, CA), Universal Studios Hollywood
(Universal City, CA), Griffith Observatory (Los Angeles, CA), Monterey Bay
Aquarium (Monterey, CA).
