# v1.4.0 Changelog "The Halls of Congress"
## Table of Contents 

[Assimilation and Immigration](#assimilation-and-immigration)

[Army](#army)

[Country Specific Changes](#country-specific-changes)

[Economy](#economy)

[National Focuses](#national-focuses)

[Navy](#navy)

[Politics](#politics)

[QoL Changes & Bugfixes](#qol-changes-and-bugfixes)

[Religion](#religion)

[War Exhaustion](#war-exhaustion)

## Army
- Changed tactics tech, it now scales better through the game

## Assimilation and Immigration
- Added +25% assimilation bonus to prestige techs.
- Made assimilation factors always scale properly between no culture core and yes culture core situations.
- Buffed assimilation focus modifier from +500% to +600%.
- Buffed base assimilation rate.
- Removed negative modifier for internal migration when state has factories.
- Increased international emigration when land is occupied.

## Country Specific Changes
- UK:
    - Pakistan now starts as an uncivilized vassal of the UK and is added to the Indian annexation system.
    - Hyderabad now starts annexed as colonial land.
    - Start with non-socialist trade unions reform.
    - Made it so you can only pass through the Gibraltar Straits by sea if you control Gibraltar province.
- USA:
    - USA starts with universal voting, allowed public meetings, upper house based on population, and secret ballots.
    - Reduced immigration attraction debuff from special modifiers for the USA.
    - Pushed back forced start date of civil war to 1860.
    - Made it so when you go over 5 revanchism, the civil war no longer fires. 
    - Homestead act decision now switches land reform to homesteading & grants +15% immigration attraction for 1 year.
    - Split Missouri & Iowa off of Kansas state.
- Other new world nations:
    - Start with wealth voting, allowed public meetings, upper house based on population, and gerrymandering.
- Russia:
    - Starts with serfdom. For russia, serfdom may only be abolished after nationalism & imperialism is invented.
- Austria:
    - Added more starting bureaucrats.
    - Starts with serfdom. If it has not yet been abolished, you will get a new 1848 revolution event, giving militancy & immediately removing serfdom.
- Balkan countries:
    - Starts with serfdom.
- Ottomans:
    - Starts with serfdom.
- China:
    - Increased research point buff of Chinese unciv modifier to 20% from 10%.
- Prussia:
    - Forming NGF now removes the cores of North German tags.
    - Forming Germany now removes the cores of South German tags and NGF.
- Yugoslavia:
    - Starting Yugoslavia cores are removed.
    - Yugoslavia formation decision is now based on owning the states themselves.
    - Forming Yugoslavia removes cores of Slovenia & Croatia.
    - Removed militancy effects from forming Yugoslavia.
    - Removed infamy gain from forming Yugoslavia.
    - Halved prestige gain from forming Yugoslavia.
- Mexico:
    - Made it so you must be at peace to click the North American hegemony decision.
- African Countries:
    - African countries may now recieve migrants

## Economy
- Raised tarriff limit to 50 under protectionism and 40 under free trade, from 40 and 20 respectively.
- Allowed investment into capitalist projects under laissez faire.
- Removed -50% army supply consumption that was applying at all times.
- Base Tax efficiency has been raised to 20% from 18%.
- Fixed small arms input bonuses to align with its input goods.
- Removed ammunition requirement for explosives factory.
- Increased fertilizer requirement for explosives factory.
- Increased output of machine parts factory.
- Increased output of several consumer goods factories.
- Split fabric factory into cotton and wool fabric factories.
- Increased base iron production significantly.
- Added RGO throughput to the power tech line in industry tech.
- Added 5% Maximum Tariff rate bonus to monetary system line in commerce tech.

## National Focuses
- Nerfed RGO national focus from +25% to +15%.
- Nerfed Throughput national focus from +15% to +10%.
- Buffed party loyalty focus, factor is now +0.01 from +0.002.
- Buffed navy national focus, it now has +15% navy repair speed.

## Navy
- Made it so each era's ships are 15x better than the previous era, so it's always worth it to upgrade.
- Added an advanced transport unit with a higher hull for the final era so that transports do not get instantly destroyed in the last era.
- Increased torpedo attack of submarine ships.
- Heavily buffed Naval Engineering tech in the two later eras.
- Buffed Naval Doctrine tech line stat buffs in the two later eras.

## Politics
- Increased cooldown between passing reforms to three years.
- Removed a lot of steps in reforms, most categories are now 3 or 4 reform levels long
- In accordance with this, all countries reforms are set to the beginning in all categories (except having appointed upper house). A few countries start with different reforms, which will be listed in their [Country-Specific Changes](#country-specific-changes) entry.
- Reworked the impacts of all reforms, they are now all positive:
    - Abolishing slavery improves pop promotion rates and migration attraction.
    - Expanding voting grants immigrant attraction and reduced militancy.
    - Expanding press rights increases education efficiency.
    - Allowing public meetings reduces militancy.
    - Political parties reform grants assimilation rate.
    - Trade Unions reform increases the maximum tarriff rate.
    - Minumum wage reform increases minimum wage and tax efficiency.
    - Unemployment subsidies reform reduces mobilization impact on economy & supply consumption of the army
    - All unlisted social reforms reduce healthcare expenses.
- Removed Healthcare & Education reforms impact on militancy.
- Reworked Military policy:
    - Removed impact on army supply consumption from all policies.
    - Removed combat nerfs from anti-military and pacifism policies.
    - Reduced combat buffs from pro-military and jingoism policies.
    - Removed cb generation speed nerf from anti-military and pacifism.
- Removed Administrative Professionalism reform's impact on administrative efficiency.
- Increased Administrative Professionalism reform's impact on education efficiency.
- Heavily reduced militancy gain for reform desire modifiers.
- Removed 1860 requirement for passing social reforms.
- Removed RGO Throughput modifier from national values.
- Removed immigration attraction impact from slavery reform.
- Added a land reform category:
    - Serfdom grants -0.05 promotion rate, -0.01 militancy, +5% rgo output, and can only be removed with a decision costing 500k.
    - Tenant farmers grants -0.025 promotion rate & +5% rgo output.
    - Homesteading grants +5% rgo output, +10% immigration attraction, and +20% assimilation rate.
    - Commercialized agriculture grants +5% rgo output & throughput, +0.025 promotion rate, -6% tax efficiency, & -5% maximum tariff rate.
    - Collectivized agriculture can only be enacted by decision under communism & can only be removed by decision if not communist. It converts all aristocrats into craftsmen & grants +5% maximum tariff as well as +6% tax efficiency.
    - Most countries start on tenant farmers, a few start on serfdom. Those on serfdom will be listed in their [Country-Specific Changes](#country-specific-changes) entry.

## QoL Changes and Bugfixes
- Added missing ports in Azov and Medan.
- Made the chance to be invented for all relevant military inventions 100%.
- Uncivilized nations can now use the transfer cb on civilized nations. It will be the host's responsibility to prevent exploiting this to turn states into colonies.
- Healthcare & Education public system reforms are now blocked if you don't have the tech to properly utilize them.    
- Removed prestige hit penalty for reassigning generals during war.
- Removed prestige hit penalty for declining call to arms.
- Updated full & limited citizenship localisation to more accurately describe its effect.
- Applied country flags by default for countries that have the appropriate tech at the start of the bookmark: This cuts down on event spam, especially in the ww1 bookmark.
- Migrated national idea system so it uses the variable system to give you national idea points that you can spend at will. This is so if you forget to click a national idea, you do not delay taking the next one.
- Added a tutorial event chain for new players.
- Fixed poptypes localisation so it no longer says "crisis state" when it should say "state"
- Ghost army event now properly removes ghost armies. Ghost navies still do not get removed & move themselves to the coast of cocos islands where the ghost nation tag is located.

## Religion
- Added religion mechanic:
    - You are allowed to pick a religion based on owning non-colonial core provinces that were historically following that religion.
    - There is a 20 year timer to select a new religion.
    - Each religion has unique bonuses.
    - You gain militancy for selecting a new religion, more for religions that were historically less popular.
    - Nations start with appropriate religions for their historical situation.
    - Shinto is specific to Japan only.
    - State Atheism may be taken by any communist nation.

## Tech Schools
- Changed cooldown to 15 years from 35 years.

## War Exhaustion
- Reduced impact on militancy from war exhaustion by 50%
- Increased war exhaustion reduction at peace to -2 from -1.
