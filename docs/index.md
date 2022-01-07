## Shadower Remaster

I'm a level 271 Shadower in MapleSEA. Been playing this class since I fell in love with it in RED, and the remaster is a significant event that's going to affect us for years to come. So I'd like to share my thoughts on the remaster while I can, whether or not it sways the decisions behind these changes.

### Convenience changes

These are the most uninteresting changes, so I'll quickly get them over with.

#### Flip the Coin Toggle

<img src="assets/flip.png">

Flip is now a toggle. Crit rate from 10% per stack to 5% per stack. Stacks are gained by landing critical hits while the toggle is on, and will stay indefinitely until toggled off or the buff is removed.

<img src="assets/criticaledge.png">

Crit rate difference is made up for in 2nd job passive, which now gives 25% crit and 5% crit damage (the average of 0% to 10% of Prima Critical at 4th job, which is now removed).

#### Meso Guard, Dagger Booster, Haste, Shadower Instinct Passive

<img src="assets/booster.png">

<img src="assets/shieldmastery.png">

Meso Guard is now a passive 60% damage reduction in Shield Mastery. Booster is renamed to Dagger Acceleration and is now passive. Haste is now completely passive.

While I appreciate having one less thing to put on pet buff, Booster being passive now makes it harder to lab and test attack speed-related mechanics.

Shadower Instinct passively gives the maximum of 70 ATT.

### Minor Skill changes / removals

#### Double Stab (and Lucky Seven) mobbing

Double Stab now hits 5 targets in a small area.

#### Dark Flare redesign

(MapleStoryT_oBux28n1h7.mp4)

Dark Flare now hits 3 targets, up from 1. Damage reflection functionality removed. Attack interval from 900ms to 930ms.

<img src="assets/flare2.png">

Time from install to first attack reduced.

<img src="assets/flare3.png">

Leftward range reduced by 1px, rightward range increased by 1px.

#### Edge Carnival mobbing skill

<img src ="assets/edge.png">

8 targets in a decent area. Vertical range larger than current Boomerang Stab. Damage adjusted from 160%x7 to 190%x4. Cast delay reduced from 840ms to 750ms.

#### Muspelheim speedup

<img src="assets/muspelheim.png">

By 30ms.

#### Smokescreen 

<img src="assets/smoke1.png">

Size increased: +40px upward range, +40px downward range, +80px leftward range. Cast delay reduced from 900ms to 810ms. Superstance while casting.

<img src="assets/smoke2.png">

Smoke no longer breaks Dark Sight when used.

### Major Skill changes / removals

#### Steal Toggle

<img src="assets/steal.png">

Steal is now a toggle that applies to all attacks. Its proc rate was reduced from 49% to 10% as a result. Mobs will drop potions that heal full HP/MP when looted. If the target stolen from is tagged as a Boss monster, the potion will give 30 ATT for 3 minutes on top of healing.

Steal still will only affect each target once ever, so it's not free sustain on a single-target boss. But if the boss has a lot of summons, it will produce potions everywhere for your pets to loot to heal and bypass potion cooldown, vastly improving self-suatain in fights like Lucid P1. In fact, it might just be ridiculously overpowered compared to other class' self-sustain which usually only heals up to 10% of their HP on a cooldown.

For farming purposes it's basically a free 10% Auto-steal line.

#### Boomerang Stab - Cruel Stab

<img src="assets/stab.png">

Skill renamed. Upward range increased by 45px, downward range increased by 35px. Damage adjusted from 375%x4 to 250%x6.

I don't understand why they keep reducing this skill's damage. First it was 742%x2, then 375%x4, now 250%x6. At first glance it's an easy tradeoff to get more lines. But with the Boomerang Stab - Bonus Attack, it went from 742%x3 = 2226%, to 375%x5 = 1875%, and then 250%x7 = 1750%. Please stop making it harder to one-shot at Hotel Arcs.

For lower-level hunting it's an improvement because more lines = more coins. But please re-adjust the damage to keep the hyper in mind.

The vertical range increase is welcome, but compared to some other toys that other classes get for their mobbing - Raging Blow has 77px higher upward range, 45px more downward range, 30px more backward range but 84px less forward range, for example - this is more like a mobbing skill you'd see on a 2015 class than a 2022 class. Please consider being more generous on the AoE.

#### Assassinate

<img src="assets/nate1.png">

Nate 1 damage decreased from 275% to 270%, downward range increased by 30px. Cast delay sped up from 840ms to 690ms.

<img src="assets/nate2.png">

Nate 2 damage increased from 350% to 490%, forward range increased by 60px, downward range increased by 30px. Flesh Nate 2 (enhanced Nate 2 from meso-weaving, more on this later) hits 50px higher and 40px forward.

Increasing the range of Nate 2 is meaningless. If you're going to make Shadowers have two different versions of their bossing skill with forced alternation, it's more than mildly annoying to have the two attacks have different ranges. I don't need more horizontal range on Nate 1, if the class concept as a melee dagger-wielder getting up close and personal is too important to sacrifice. But do increase its vertical range to match Nate 2, because it produces situations where wound stacks hit things that you wouldn't expect.

(The latter phenomenon isn't as much of a problem anymore because Wound stacks now prioritise highest-HP targets, but it's still fundamentally bad design to have the bossing skill involuntarily change AoE; the effective AoE is just going to be the smaller once.)

#### New Skills: Bloody Pocket, Bloody Explosion

<img src="assets/bloodypocket.png">

<img src="assets/bloodyex.png">

Because of the removal of Prima Critical and Shadower Instinct, Bloody Pocket gets Prima Critical's 20% crit damage passive and Shadower Instinct's Killing Points has been replaced with a Flesh buff, which is consumed to enhance the next Nate 2 to deal 100% increased final damage. The Flesh buff is obtained when Bloody Explosion hits an enemy.

Bloody Pocket is the Shadower's version of an Enrage bossing-type toggle. It replaces Pickpocket to drop red-coloured coins instead of gold ones, and replaces Meso Explosion with Bloody Explosion. While Meso Explosion is a skill that activates the coins around you to seek out enemies and home in on them, Bloody Explosion is a fixed attack with a well-defined hitbox in front of you that matches Nate 1. This attack does 240%x5 damage, and each line is increased by 10%p per red coin used. Bloody Explosion has a 0.7 second cooldown.

Meso Explosion does 100%x2 per coin, but this is increased by 20%p with the Greed passive at 3rd job, so it does 240% per coin. Bloody Explosion does 250%x5 = 1250% at one coin, but damage per coin increases only by 50% instead of 240%. At 6 coins, Meso Explosion would deal 1440% damage while Bloody Explosion would deal 1500% damage, and at any higher than 6 coins Bloody Explosion actually does less damage than Meso Explosion.

So Bloody Explosion does less damage than Meso Explosion at 7+ coins, has a cooldown while Meso Explosion does not, and has a cast animation while Meso Explosion does not. It doesn't look good at all.


<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
