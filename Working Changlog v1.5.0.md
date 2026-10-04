# Companion Balance Mod v1.5.0

## Springtime of Nations
- A new springtime of nations event chain has been added which will fire in 1848.
    - Two variables will be used during this event chain: Chaos and Liberalization. 
    - Chaos causes a modifier to be gained visible in your politics menu adding militancy, reducing factory throughput, and reducing rgo output.
    - Liberalization causes reforms to be added at the end of the event chain, and possibly government changes.
    - Throughout the event chain, each event will have three choices to either gain both chaos and liberalization, lose both chaos and liberalization, or lose chaos, only available if you already had relevant reforms.
    - If chaos reaches 0 at any point, the event chain will end immediately. Otherwise, it will end after all events have been seen.

## Great Powers
- 1 nation may be a great power at a time.
- Great power status changes in one day.
- Nations up to rank 32 are secondary powers. (for colonization)
- Spheres of influence are removed.
- Being a great power no longer grants any extra research points.
- Great powers gain double the leadership of regular nations.
- Foreign inveestment is now always disallowed.

## Economy
- Removed artisan production. Instead, artisans now work in factories making 1/3 of the throughput per worker that craftsmen do.
- All countries have added (mostly basic) industries in order to give artisans work, including uncivilized nations.
- As such, promotion is adjusted: Artisans will now never promote, and will slowly promote into craftsmen. Other pops still promote into craftsmen as usual.
- Steamer shipyards now require more coal and steel, as well as lumber and machine parts.
- Reduced input requirements of telephone and radio factories.
- Increased input requirements of all military factories.
- Naval base tech now increases steamer shipyard input requirement.
- All navies now require steamers instead of clippers.
- Frigates & Man O' Wars no longer require artillery.
- Clipper shipyards are removed & artisans no longer produce clippers.
- Increased base throughput of machine parts factory (Increased both input and output proportionally).
- Reduced upkeep goods requirements for all factories.
- Moved Advanced Forest Management technology to Practical Steam Engine and increased it to +100% timber output.
- Increased regular clothes demand of farmers, labourers, artisans, and clerks.
- Added +10% machine parts and cement throughput to Mechanization tech line in industry.

## Promotion & Literacy
- Increased promotion rate bonus from literacy.
- Reduced base promotion rate.
- Reduced global education speed.

## Buildings
- Reduced factory build/expand time to 60 days.
- Reduced fort build time to two years
- Reduced naval base build time to 180 days.

## Country-Specific Changes
- Russia: 
    - Lithuania, Latvia, and Estonia are now Estonian and are accepted at the same time as Ruthenian. 

- Scandinavia:
    - Estonian is gained as an accepted culture with State & Government.

- Spain:
    - Removed accepting portuguese, mexican, and filipino as well as the iberian union and spanish empire path options.
    - Added decision to form viceroyalties in the americas:
        - Viceroyalties may be formed by vassalizing or annexing the core lands required.
        - Viceroyalties are automatically vassalized by spain upon being formed.
        - Viceroyalties get the entire previous era of military techs for free when a new era unlocks.
        - Spain gets a viceroyalty tax event annually that takes half of the treasury of the viceroyalties, using 50k increments to calculate it up to a maximum of 1m pounds in treasury (so 500k tax excised each at maximum).
        - Spanish culture pops under Spanish rule only migrate to viceroyalties, and never to other immigrant nations. Viceroyalties can also recieve other immigrants as normal.
        - There is a special cb for spain with no infamy and 25ws cost to vassalize these tags again if they break free no matter their size. It must be justified and cannot be used to trucebreak.

- Japan:
    - Japan no longer has decisions to request sphering
    - Greater east asian co-prosperity sphere no longer grants +influence as that modifier is now useless.

- Prussia:
    - Now starts with cores over all land required to form NGF.
    - Upon forming NGF, gains cores over South Germany, then by decision can gain cores over Alsace-Lorraine once South Germany is annexed.

- Mexico:
    - North American Hegemony decision now requires ownership of an american core that isnt a mexican core instead of requiring the united states to not be a great power.

- UK:
    - Reduced starting navy size.

- France:
    - Reduced starting navy size.
    - Added French union decision which grants bonus assimilation on Maghrebi culture pops, able to be taken with State & Government.
    - Changed some terrain in the Northeast of the country to improve defensive lines.

- African Nations:
    - Added starting cores on the uncolonized parts of africa. It is both a buff to these nations and so the assimilation focus may be used here by other nations even if the African nations never owned the land.

- China:
    - China may now be formed if the country forming it is the only remaining Chinese contender (or the other contenders are vassals, either of you or another power), land ownership and civilization requirements are removed. 
    - Added treaty port provinces along the Chinese coast with a special cb for taking them. For each treaty port owned by a non-Chinese power, a flat monetary bonus is gained anually based on the current year. This ranges from 50k to 1 million each. Each treaty port owned by a Chinese power grants them +2.5% research points.
    - If the treaty ports are owned by a chinese power, but another chinese power owns the corresponding state inland from the coast, the nation owning the inland state may seize the ports by decision.

## Province Selector
- Removed economic aid campaign.
- Added research centers that are gained every research point tech. These provide +10% research points and +5% life rating, and do not disappear when a province changes owners.

## Combat
- Shock Infantry now has 1 siege.
- Tanks now have 2 siege instead of 1.

## Rebels
- Useless rebel types are removed. These include:
    - Pan-Nationalist rebels (These systems are different already anyway)
    - Carlist rebels
    - Boxer rebels
    - Italian redshirts
    - Indian sepoys
    - Native American rebels
- Rebels now no longer change any reforms besides voting and upper house composition.
- Rebels now give you a four-year "Unstable Government" modifier when they overthrow the government. This modifier grants -0.1 prestige, -2% tax efficiency, -25% land organization, -100% leadership, and -5 starting land experience.

## Politics
- Removed militancy impact from voting reforms.
- Changed public meetings reform to a new policing reform with five options. These modify militancy gain, tax efficiency, suppression point gain, and migration attraction at different levels.
- Crime fighting is now always at maximum.
- Commercialized agriculture tax efficiency malus is now -2% instead of -6%.
- Doubled promotion bonus from commercialized agriculture.
- Doubled promotion maluses from tenant farmers and serfdom.
- Added a flat malus to promotion from slavery
- Increased healthcare spending reductions from social reforms.

## Casus Bellis
- Demand concession cb can no longer be used on vassals.
- Removed add to sphere and remove from sphere cbs.

## WW1
- Bulgaria may no longer take its decisions for accepted pops in the ww1 bookmark.
- Capitulation events are now enabled by a simple host decision, and the german decisions to start ww1 are removed.
- Leadership is now gained via a decision instead of an event to prevent it from bugging in multiplayer.

## Fixes & QoL
- Collectivized agriculture now correctly prevents promotion of aristocrats.
- Rich strata pops now promote correctly.

## Technology
- Reduced each rp tech by 10% to compensate for the research centers.
