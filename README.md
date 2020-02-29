# Weapon and Item Balance - Alpha 18

**Description:**

Changes weapon and item damage to scale based primarily on their level/tier and less on random values.

My primary goal was to make it so that you never run across a higher level weapon that does more damage than a lower level weapon. To do so, I made the random damage variance 0% to 10% (from -15% to 15%), but buffed the actual damage bonus you get from levels. The actual damage amount stays roughly the same to vanilla, but without such a wild variance in damage between levels. Never again will you be disappointed when you find a level 3 weapon that out-does the damage of your level 5 weapon.

Previously, you gained a 10% buff to damage per item/weapon level, so it looked like this:

Tier 1: 0%, Tier 2: 10%, Tier 3: 20%, Tier 4: 30%, Tier 5: 40%, Tier 6: 50%

With this mod, it now looks like this:

Tier 1: 0%, Tier 2: 10%, Tier 3: 20%, Tier 4: 40%, Tier 5: 55%, Tier 6: 75%

I also reduced the damage buff you get from gear mods from 10% to 5% per mod. Which means that although my percentages per weapon level are higher, the actual max damage per weapon level isn't that much different than vanilla because the buff from mods is less.

**Notes:**

Tier 4 is 20% more than Tier 3 because it goes up a tier, but doesn't get an extra mod slot. I felt it fair to balance it that way.

Tier 6 is 20% more than tier 5 as tier 6 is uncraftable and meant to be rare/legendary/epic, so it's a bonus to find it.

The formula for how damage is calculated is as such:

Base Damage + Random Damage (0%-10%) + Level Bonus + 5% per filled mod slot

So a Level 4 perfect rolled weapon that does 100 base damage would be this:

100 + 15% + 40% + 5% + %5, which would come out to 165 damage.

**Compatibility Notes:**

This should work with any version of Alpha 18. Since it's only done using XML edit, it's only required on the server. Clients don't need to download it because the changes will get pushed to them automatically.