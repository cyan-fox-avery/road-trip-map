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

## Places so far (460)

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
MT), Montana Vortex and House of Mystery (Columbia
Falls, MT), CSKT Bison Range (Moiese, MT), Gates of
the Mountains Boat Tours (Helena, MT), Grizzly &
Wolf Discovery Center (West Yellowstone, MT),
Alpacas of Montana, Inc. (Bozeman, MT), Tinkertown
Museum (Sandia Park, NM), Kakawa Chocolate House
(Santa Fe, NM), Cumbres & Toltec Scenic Railroad
(Chama, NM), Sparky's Burgers, BBQ & Espresso
(Hatch, NM), 66 Diner (Albuquerque, NM), Spaceport
Roswell (Roswell, NM), Indian Pueblo Cultural
Center (Albuquerque, NM), Sandia Peak Tramway
(Albuquerque, NM), Bosque del Apache National
Wildlife Refuge (San Antonio, NM), Terry Bison
Ranch Resort (Cheyenne, WY), Bar T 5 Covered Wagon
Cookout and Show (Jackson, WY), Chugwater Soda Fountain
(Chugwater, WY), Farson Mercantile (Farson, WY), Cody
Cattle Company (Cody, WY), Cody Nite Rodeo (Cody, WY),
Wyoming Dinosaur Center (Thermopolis, WY), Buffalo Bill
Center of the West (Cody, WY), Yellowstone National Park
(WY), Grand Teton National Park (WY), Acadia National Park
(Bar Harbor, ME), Bryce Canyon National Park (UT),
Everglades National Park (FL), Glacier National Park (MT),
Rocky Mountain National Park (CO), Sequoia & Kings Canyon
National Parks (CA), Zion National Park (UT), Wind River Canyon
(Thermopolis, WY), Hell's Half Acre (Casper, WY), Devils Tower
National Monument (Devils Tower, WY), Cody (Cody, WY), Jackson
(Jackson, WY), National Elk Refuge Sleigh Rides (Jackson, WY),
The Airplane Restaurant (Colorado Springs, CO), Manitou Springs
Penny Arcade (Manitou Springs, CO), The Wizard's Chest (Denver, CO),
Fifty Two 80's — A Totally Awesome Shop (Denver, CO), Sasquatch Outpost
(Bailey, CO), Butterfly Pavilion (Westminster, CO), Hammond's Candies
Factory (Denver, CO), Dinosaur Ridge (Morrison, CO), Ghost Town Museum
(Colorado Springs, CO), Manitou Springs (Manitou Springs, CO), Pikes Peak Cog Railway (Manitou Springs, CO), Glenwood Caverns Adventure Park (Glenwood Springs, CO), Royal Gorge Bridge & Park (Cañon City, CO), Royal Gorge Route Railroad (Cañon City, CO), Glenwood Hot Springs Pool (Glenwood Springs, CO), Georgetown Loop Railroad (Georgetown, CO), Durango & Silverton Narrow Gauge Railroad (Durango, CO), Black Canyon of the Gunnison National Park (Montrose, CO), Chama Gaúcha
Brazilian Steakhouse (Houston, TX), Adega Gaucha Brazilian Steakhouse
(Orlando, FL), Brasão Brazilian Steakhouse (San Antonio, TX), Galpão Gaucho
Brazilian Steakhouse (Las Vegas, NV), Show de Carnes Brazilian Steakhouse
(Palo Alto, CA), Bullvino's Churrascaria (St. Paul, MN), M Grill Brazilian
Churrascaria (Los Angeles, CA), Rodizio Grill Brazilian Steakhouse (Denver,
CO), Fogo de Chão — Naperville (Naperville, IL), Texas de Brazil — Irvine
(Irvine, CA), Ghirardelli Square (San Francisco, CA), Flaming Gorge Reservoir (Dutch John, UT), Taos (Taos, NM), Carmel-by-the-Sea (Carmel-by-the-Sea, CA), Monterey (Monterey, CA), Turpentine Creek Wildlife Refuge (Eureka Springs, AR), Peaceful Valley Donkey Rescue (San Angelo, TX), Lions Tigers & Bears (Alpine, CA), Wild Spirit Wolf Sanctuary (Ramah, NM), Chimp Haven (Keithville, LA), Luvin Arms Animal Sanctuary (Erie, CO), The Gentle Barn (Santa Clarita, CA), Farm Sanctuary (Watkins Glen, NY), Animal Place (Grass Valley, CA), Woodstock Farm Sanctuary (High Falls, NY), Full Circle Farm Sanctuary (Warm Springs, GA), Save the Chimps (Fort Pierce, FL), Warm Springs Ranch (Boonville, MO), Acadia by Carriage (Acadia National Park, ME), Wild Horse Adventure Tours (Corolla, NC), Kentucky Horse Park (Lexington, KY), Old Friends (Georgetown, KY), Retirement Home for Horses (Alachua, FL), Assateague Island (Berlin, MD), Return to Freedom (Lompoc, CA), Salt River Wild Horse Viewing (Mesa, AZ), Pryor Mountain Wild Mustang Center (Lovell, WY), Biltmore Estate Carriage & Trail Ride Barns (Asheville, NC), Mackinac Island Carriage Tours (Mackinac Island, MI), Fort Worth Stockyards (Fort Worth, TX), Palo Duro Canyon State Park (Canyon, TX), National Videogame Museum (Frisco, TX), Grapevine (Grapevine, TX), Fossil Rim Wildlife Center (Glen Rose, TX), Buc-ee's — Luling (Luling, TX), Lockhart (Lockhart, TX), The Salt Lick BBQ (Driftwood, TX), Dr Pepper Museum (Waco, TX), Blue Bell Creameries (Brenham, TX), Museum of the Weird (Austin, TX), Capital Cruises Bat-Watching Tour (Austin, TX), Space Center Houston (Houston, TX), San Antonio River Walk (San Antonio, TX), Meow Wolf Houston (Houston, TX), Beer Can House (Houston, TX), Moody Gardens (Galveston, TX), Galveston Historic Seaport (Galveston, TX), Sea Turtle, Inc. (South Padre Island, TX), Captain Ron's Swamp Tours (Uncertain, TX), Big Bend National Park (Big Bend National Park, TX), McDonald Observatory (Fort Davis, TX), Pops 66 Soda Ranch (Arcadia, OK), Decopolis (Tulsa, OK), Buck Atom's Cosmic Curios on 66 (Tulsa, OK), Joseph H. Williams Tallgrass Prairie Preserve (Pawhuska, OK), Waylan's Ku-Ku Burger (Miami, OK), Oklahoma Aquarium (Jenks, OK), Woolaroc Museum & Wildlife Preserve (Bartlesville, OK), Factory Obscura: Mix-Tape (Oklahoma City, OK), Express Clydesdales Ranch (Yukon, OK), The American Pigeon Museum & Library (Oklahoma City, OK), First Americans Museum (Oklahoma City, OK), Sam Noble Oklahoma Museum of Natural History (Norman, OK), Stockyards City (Oklahoma City, OK), Sid's Diner (El Reno, OK), Eischen's Bar (Okarche, OK), Stafford Air & Space Museum (Weatherford, OK), Wichita Mountains Wildlife Refuge (Indiahoma, OK), Medicine Park (Medicine Park, OK), Meers Store & Restaurant (Meers, OK), Talimena Scenic Byway (Talihina, OK), Salt Plains National Wildlife Refuge — Crystal Digging (Cherokee, OK), Chickasaw Cultural Center (Sulphur, OK), Mardi Gras World (New Orleans, LA), JAMNOLA (New Orleans, LA), Music Box Village (New Orleans, LA), Leroy's Place Art & Gifts (New Orleans, LA), New Orleans Pharmacy Museum (New Orleans, LA), New Orleans School of Cooking (New Orleans, LA), Dead of Night Ghosts and Cemetery Bus Tour (New Orleans, LA), Parkway Bakery & Tavern (New Orleans, LA), Steamboat Natchez (New Orleans, LA), Angelo Brocato (New Orleans, LA), Whitney Plantation (Wallace, LA), Abita Mystery House (Abita Springs, LA), Louisiana's Old State Capitol (Baton Rouge, LA), Last Wilderness Swamp Tours (Plaquemine, LA), Champagne's Cajun Swamp Tours (Breaux Bridge, LA), TABASCO Factory Tour & Avery Island (Avery Island, LA), Rip Van Winkle Gardens (New Iberia, LA), Vermilionville Historic Village (Lafayette, LA), Creole Nature Trail Adventure Point (Sulphur, LA), Chauvin Sculpture Garden (Chauvin, LA), Historic Downtown Natchitoches (Natchitoches, LA), Mardi Gras Museum of Imperial Calcasieu (Lake Charles, LA), Shreveport Water Works Museum (Shreveport, LA), Biedenharn Coca-Cola Museum & Gardens (Monroe, LA), Cosmosphere (Hutchinson, KS), Lucas (Lucas, KS), Strataca, Kansas Underground Salt Museum (Hutchinson, KS), Monument Rocks (Oakley, KS), Little Jerusalem Badlands State Park (Oakley, KS), Rock City Park (Minneapolis, KS), Tallgrass Prairie National Preserve (Strong City, KS), Maxwell Wildlife Refuge (Canton, KS), Gypsum Hills Scenic Byway (Medicine Lodge, KS), Lindsborg (Lindsborg, KS), OZ Museum (Wamego, KS), Atlas9 (Kansas City, KS), Abilene & Smoky Valley Railroad (Abilene, KS), Moon Marble Company (Bonner Springs, KS), Joe's Kansas City Bar-B-Que (Kansas City, KS), Nifty Nut House (Wichita, KS), Museum of World Treasures (Wichita, KS), Big Brutus (West Mineral, KS), Old Mill Tasty Shop (Wichita, KS), Boot Hill Museum (Dodge City, KS), Ellinwood Underground Tunnel Tours (Ellinwood, KS), Brown v. Board of Education National Historical Park (Topeka, KS), Hastings Museum (Hastings, NE), Ashfall Fossil Beds State Historical Park (Royal, NE). Omaha's Henry Doorly Zoo and Aquarium (Omaha, NE), The Old Market (Omaha, NE), Kiewit Luminarium (Omaha, NE), The Durham Museum (Omaha, NE), Hollywood Candy (Omaha, NE), The Drover (Omaha, NE), Lee G. Simmons Wildlife Safari Park (Ashland, NE), Museum of American Speed (Lincoln, NE), Strategic Air Command & Aerospace Museum (Ashland, NE), Morrill Hall — University of Nebraska State Museum (Lincoln, NE). Bigfoot Crossroads of America Museum (Hastings, NE), Fort Cody Trading Post (North Platte, NE), The Archway Museum (Kearney, NE), Carhenge (Alliance, NE), Scotts Bluff National Monument (Gering, NE), Merritt Reservoir State Recreation Area (Valentine, NE), The Potter Sundry (Potter, NE), Badlands National Park (Interior, SD), Custer State Park Wildlife Loop Road (Custer, SD), Needles Highway (Custer, SD), Iron Mountain Road (Keystone, SD), Spearfish Canyon Scenic Byway (Spearfish, SD), Mount Rushmore National Memorial (Keystone, SD), Crazy Horse Memorial (Custer, SD), The Mammoth Site (Hot Springs, SD), Black Hills Institute Museum (Hill City, SD), Jewel Cave National Monument (Custer, SD), Minuteman Missile National Historic Site (Philip, SD), Wind Cave National Park (Hot Springs, SD), Wall Drug (Wall, SD), Porter Sculpture Park (Montrose, SD), Corn Palace (Mitchell, SD), Cosmos Mystery Area (Rapid City, SD), Dahl's Chainsaw Art (Keystone, SD), Deadwood (Deadwood, SD), 1880 Train (Hill City, SD), Big Thunder Gold Mine (Keystone, SD), 1880 Town (Midland, SD), The Brothel Deadwood (Deadwood, SD), Dignity of Earth and Sky (Chamberlain, SD), National Music Museum (Vermillion, SD), Falls Park (Sioux Falls, SD), Theodore Roosevelt National Park — South Unit (Medora, ND), Theodore Roosevelt National Park — North Unit (Watford City, ND), Painted Canyon (Belfield, ND), International Peace Garden (Dunseith, ND), Pembina Gorge (Walhalla, ND), White Horse Hill National Game Preserve (St. Michael, ND), Frontier Village (Jamestown, ND), Enchanted Highway (Gladstone, ND), Scandinavian Heritage Park (Minot, ND), Fargo-Moorhead Visitors Center (Fargo, ND), Salem Sue (New Salem, ND), Dickinson Museum Center (Dickinson, ND), Paul Broste Rock Museum (Parshall, ND), North Dakota Heritage Center & State Museum (Bismarck, ND), Fargo Air Museum (Fargo, ND), Dakota Territory Air Museum (Minot, ND), Medora (Medora, ND), Ronald Reagan Minuteman Missile State Historic Site (Cooperstown, ND). Bonanzaville, USA (West Fargo, ND), Fort Abraham Lincoln State Park (Mandan, ND), Lewis & Clark Riverboat (Bismarck, ND), Knife River Indian Villages National Historic Site (Stanton, ND), Prairie Fire Pottery (Beach, ND), Pitchfork Steak Fondue (Medora, ND), Villalobos Rescue Center (New Orleans, LA), Krispy Kreme Doughnut Factory (Winston-Salem, NC), World of Coca-Cola (Atlanta, GA), Enchanted Forest (Turner, OR). Crater of Diamonds State Park (Murfreesboro, AR), Ron Coleman Mining (Jessieville, AR), Blanchard Springs Caverns (Fifty-Six, AR), Hot Springs National Park (Hot Springs, AR), Garvan Woodland Gardens (Hot Springs, AR), Mid-America Science Museum (Hot Springs, AR), Eureka Springs Downtown (Eureka Springs, AR), Thorncrown Chapel (Eureka Springs, AR), War Eagle Mill (Rogers, AR), Bigfoot: The Curator's Collection (Eureka Springs, AR), Crystal Bridges Museum of American Art (Bentonville, AR), The Momentary (Bentonville, AR), Petit Jean State Park (Morrilton, AR), ESSE Purse Museum (Little Rock, AR), Buffalo National River (St. Joe, AR), Oark General Store (Oark, AR), Silver Dollar City (Branson, MO), Fantastic Caverns (Springfield, MO), The Rabbit hOle (North Kansas City, MO), Wonders of Wildlife National Museum & Aquarium (Springfield, MO).
