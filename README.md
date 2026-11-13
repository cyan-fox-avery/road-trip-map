# Road Trip Map

An interactive map for Avery, Harley, and Sarah to plan a road trip across the
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

## Places so far (184)

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
Aquarium (Monterey, CA), Santa Cruz Beach Boardwalk (Santa Cruz, CA),
Exploratorium (San Francisco, CA), Alcatraz Island (San Francisco, CA),
Skunk Train (Fort Bragg, CA), Redwood Sky Walk (Eureka, CA), The Living
Desert Zoo & Gardens (Palm Desert, CA), Cranberry Sweets & More (Coos Bay,
OR), New England Aquarium (Boston, MA), Tillamook Creamery (Tillamook, OR),
Freakybuttrue Peculiarium (Portland, OR), Crater Lake Rim Drive (Crater
Lake National Park, OR), Rogue Creamery Cheese Shop (Central Point, OR),
Roaring Rapids Pizza (Eugene, OR), Slappy Cakes (Portland, OR), Raven's
Manor (Portland, OR), Paxton Gate (Portland, OR), Marsh's Free Museum
(Long Beach, WA), Sharky's (Ocean Shores, WA), Archie McPhee (Seattle,
WA), Ye Olde Curiosity Shop (Seattle, WA), Pike Place Market (Seattle,
WA), Snoqualmie Falls (Snoqualmie, WA), Leavenworth Reindeer Farm
(Leavenworth, WA), Petunia & Loomis (Spokane, WA), Numerica SkyRide
(Spokane, WA), Bright's Candies (Walla Walla, WA), Chukar Cherries
(Prosser, WA), The Gingerbread Factory (Leavenworth, WA), SPARK Museum
of Electrical Invention (Bellingham, WA), Poulsbo (Poulsbo, WA), Las
Vegas (Las Vegas, NV), AREA15 (Las Vegas, NV), The Golden Tiki (Las
Vegas, NV), Silverton Aquarium (Las Vegas, NV), Ethel M Chocolates
Factory & Cactus Garden (Henderson, NV), Hoover Dam (Boulder City,
NV), Northshore Road (Boulder City, NV), Extraterrestrial Highway
(Rachel, NV), Virginia City (Virginia City, NV), Virginia & Truckee
Railroad (Virginia City, NV), Junkee Clothing Exchange (Reno, NV),
Nevada Northern Railway (Ely, NV), The Star Hotel (Elko, NV),
Sandpoint (Sandpoint, ID), Silverwood Theme Park (Athol, ID), Lake
Coeur d'Alene Cruises (Coeur d'Alene, ID), Wallace (Wallace, ID),
Silver Mountain Gondola (Kellogg, ID), Boise (Boise, ID), RePop
Gifts (Boise, ID), Westside Drive In (Boise, ID), Indian Creek
Plaza (Caldwell, ID), Bruneau Dunes State Park (Bruneau, ID),
McCall (McCall, ID), The Roundhouse (Sun Valley, ID), Shoshone
Falls (Twin Falls, ID), Pickle's Place (Arco, ID), Craters of the
Moon National Monument (Arco, ID), Lava Hot Springs Hot Pools
(Lava Hot Springs, ID), Idaho Potato Museum (Blackfoot, ID),
Willie's Chicken Shack (New Orleans, LA), New Orleans (New
Orleans, LA), Café du Monde (New Orleans, LA), Pepper Palace
(New Orleans, LA), Audubon Aquarium (New Orleans, LA), Café
Pontalba (New Orleans, LA), Johnny Longboats (Riviera Beach, FL),
Four Corners Monument (Teec Nos Pos, AZ), Jelly Belly Factory (Fairfield,
CA), Bravo Farms Gift Shoppe (Traver, CA), Peggy Sue's 50's Diner (Yermo,
CA), Calico Ghost Town (Yermo, CA), Old Sacramento Waterfront (Sacramento,
CA), Rosicrucian Egyptian Museum (San Jose, CA), Yosemite Valley Scenic
Drive (Yosemite National Park, CA), Springfield (Springfield, OR),
Hot Lake Springs Resort (La Grande, OR), Sumpter Valley Railroad
(Sumpter, OR), Painted Hills Scenic Drive (Mitchell, OR), Liberty
Orchards Aplets & Cotlets Factory (Cashmere, WA), LIGO Exploration
Centre (Richland, WA), North Cascades Highway (Rockport, WA), Grand
Canyon South Rim (Grand Canyon Village, AZ), Bearizona (Williams, AZ),
Poozeum (Williams, AZ), Seligman (Seligman, AZ), Oatman (Oatman, AZ),
Keepers of the Wild (Valentine, AZ), Meteor Crater (Winslow, AZ),
Petrified Forest National Park (Holbrook, AZ), Lowell Observatory
(Flagstaff, AZ), Verde Canyon Railroad (Clarkdale, AZ), Organ Stop Pizza
(Mesa, AZ), Curious Nature (Phoenix, AZ), OdySea Aquarium (Scottsdale,
AZ), Butterfly Wonderland (Scottsdale, AZ), Cerreta Candy Company
(Glendale, AZ), Rustler's Rooste (Phoenix, AZ), Trail Dust Town
(Tucson, AZ), Bowlin's The Thing (Dragoon, AZ), Matelot Gulch
Mining Company (Columbia, CA), Wegner Crystal Mines (Mount Ida,
AR), Rose Creek Mine (Franklin, NC), Sheffler Rock Shop and
Geode Mine (Alexandria, MO), Herkimer Diamond Mines (Herkimer,
NY), Rainforest Cafe — Mall of America (Bloomington, MN), Casa
Bonita (Lakewood, CO), Fritz's Railroad Restaurant (Kansas City,
MO), Lambert's Cafe (Sikeston, MO), Magic Time Machine (San
Antonio, TX), Aquarium Restaurant — Houston (Houston, TX),
Mai-Kai Restaurant (Fort Lauderdale, FL), Tonga Room &
Hurricane Bar (San Francisco, CA), Dooky Chase's Restaurant
(New Orleans, LA), The Big Texan Steak Ranch (Amarillo, TX),
Serendipity 3 (New York, NY), Cattleman's Steakhouse at
Indian Cliffs Ranch (Fabens, TX), Harris Ranch Resort
(Coalinga, CA), Skeletons: Museum of Osteology (Oklahoma
City, OK), National Museum of Funeral History (Houston, TX),
Museum of Bad Art (Boston, MA), Moab (Moab, UT), Arches
National Park (Moab, UT), Museum of Jurassic Technology
(Culver City, CA), International UFO Museum and Research
Center (Roswell, NM), American Museum of Magic (Marshall,
MI), The Strong National Museum of Play (Rochester, NY),
National Comedy Center (Jamestown, NY), Museum of Pop
Culture (Seattle, WA), Steven F. Udvar-Hazy Center
(Chantilly, VA), Museum of the Moving Image (Astoria, NY),
Field Museum of Natural History (Chicago, IL), National
Museum of Natural History (Washington, DC), Atomic Museum
(Las Vegas, NV), American Visionary Art Museum (Baltimore,
MD), American Sign Museum (Cincinnati, OH), Gilgal
Sculpture Garden (Salt Lake City, UT), Hollow Mountain
(Hanksville, UT), Bonneville Salt Flats (Wendover, UT),
Hole N" The Rock (Moab, UT), Prairie Schooner Steak House
(Ogden, UT), Pirate O's Gourmet Market (Draper, UT),
Gardner Village (West Jordan, UT), Moab Rock Shop (Moab,
UT), Heber Valley Milk & Artisan Cheese (Midway, UT),
Loveland Living Planet Aquarium (Draper, UT), Mrs.
Cavanaugh's Chocolates and Ice Cream (North Salt Lake,
UT), Himitsu Station (Salt Lake City, UT), This Is The
Place Heritage Park (Salt Lake City, UT), Sip 'n Dip
Lounge (Great Falls, MT), The Sweet Palace
(Philipsburg, MT), Montana Gems of Philipsburg
(Philipsburg, MT), St. Regis Travel Center (St. Regis,
MT).
