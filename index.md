---
layout: default
---

# Riff's Guide to Subtlety Rogue

Welcome to my guide to Subtlety Rogue for 7.2. If you're looking for a good
introduction to playing Subtlety in Legion, you've come to the right place.

I'll make a note of any changes to the guide and the date it was updated here if
you want to come back in the future to check for changes.

**Last updated: Tuesday 23rd May 2017 - Added details about the Shadow
Dance/Stealth pre-pull**

<div id="toc"></div>

## Introduction

Subtlety got a pretty big overhaul for Legion. The biggest change being Shadow
Dance. Previously a 1 minute cool down that lasted for 8 seconds. Now a 1 minute
cool down that lasts for 3 seconds, with 3 charges. The new Deepening Shadows
passive reducing the remaining cool down of Shadow Dance by 3 seconds per combo
point spent.

We also got back Shadowblades as our major cool down ability. We also got a
replacement for Slice and Dice in the form of Symbols of Death, which is a self
buff we can only use from Stealth to increase our damage by 20%.

Subtlety isn't the outright strongest Rogue specialization right now, but with
the right legendaries (if you're lucky) you can compete with others.

## Talents

Subtlety talents are mostly cookie cutter except for the level 15 talents, and
the survivability talents at level 60.

- Level 15: Master of Subtlety
- Level 30: Subterfuge
- Level 45: Deeper Stratagem or Anticipation<sup>1</sup>
- Level 60: Elusiveness or Cheat Death
- Level 75: Prey on the Weak
- Level 90: Premeditation
- Level 100: Master of Shadows

1: Anticipation can be better if you have the Denial of the Half-Giants bracers.
You may want to use Anticipation over Deeper Stratagem to avoid combo point
wastage if you have Tier 19 4 set bonus.

## Artifact

Our artifact are the Fangs of the Devourer. Pretty much the teeth of Sargeras'
puppy dog, Goremaw the Devourer.

### Traits

At this point in the expansion, a lot of characters will be at 25 artifact
knowledge or at least close to it. So filling out 34 traits is fairly quick, and
you'll have the 3 golden traits easily.

If you do require the routes you should take, you can follow these routes in
order.

- Gutripper
- Catlike Reflexes
- Ghost Armor
- Energetic Stabbing
- Finality
- Flickering Shadows
- The Quiet Knife
- Akaari's Soul
- Demon's Kiss
- Precision Strike
- Soul Shadows
- Shadow Nova
- Fortune's Bite
- Second Shuriken
- Embrace the Darkness

Then you want to get Legionblade, and once you've empowered your artifact you
can unlock the new traits.

- Shadows of the Uncrowned
- Etched in Shadow
- Shadow's Whisper
- Feeding Frenzy

Once you've got the 4th gold trait you can fill out 4/4 in the other powerful
traits.

- Energetic Stabbing
- Gutripper
- Demon's Kiss
- Precision Strike
- Fortune's Bite
- Soul Shadows
- The Quiet Knife

Then 4/4 in the less useful traits

- Catlike Reflexes
- Ghost Armor

### Relics

- Energetic Stabbing
- Gutripper
- Demon's Kiss
- Precision Strike
- Fortune's Bite
- Soul Shadows
- The Quiet Knife

You should always run a simulation of your character to check if a higher item
level relic might be better than your current relic.

## Gearing &amp; Stats

Gearing in Legion has become a lot more complicated in the sense that warforged,
titanforged, and sockets make picking your best items more difficult, even if
they're a lower item level.

When in doubt, you should run simulations of your character to compare the item
or multiple items.

You may also be familiar with the term **stat weights**, this term is complete
bullshit. For a start it's **scale factors**, and secondly your scale factors
will become out of date whenever you equip a new item. It's always better to run
a simulation of your character to compare items to see if it's an upgrade. This
excludes trinkets as some times they're not modelled correctly in simulations.

For stats you should be aiming for the following:

- Agility
- Mastery
- Versatility
- Critical Strike
- Haste

Certain items may change which stats you will want. For example Mantle of the
Master Assassin will make Critical Strike less important and Insignia of
Ravenholdt will bring Versatility ahead of Mastery.

**When in doubt, run a simulation for your character and the item(s) in
question.**

For your food buff while raiding you should use the food for the secondary stat
that you're scale factors says is highest.

For potions you should use Potion of the Old War, or if you're saving gold Potion
of Prolonged Power (which is also best on AoE as well).

For your flask you should always use Flask of the Seventh Demon.

#### Legendaries

- Mantle of the Master Assassin
- Shadow Satyr's Walk
- Denial of the Half-Giants
- Insignia of Ravenholdt
- Cinidaria, the Symbiote
- The Dreadlord's Deceit

## Rotation

### Pre-Pull

- Before the pull timer, Symbols of Death
- 5 seconds on the pull timer, Symbols of Death, and then come out of stealth
- 1 second on the pull timer, use Shadow Dance, Stealth, and Potion
  macro<sup>2</sup>

2: See [macros](#macros) for the Shadow Dance, Stealth, and Potion macro. More
details about this can be found in the [FAQ
section](#frequently-asked-questions).

### Pull

- Shadowblades
- Shadowstrike
- Shadowstrike
- Nightblade

### Priorities

- Symbols of Death, refresh with 10.5 seconds or less remaining

#### At 5-6 Combo Points

- Nightblade, refresh with 5.4 seconds remaining at 6 combo points, or 4.7
  seconds remaining at 5 combo points<sup>3</sup>
- Eviscerate

3: You do not want to overwrite a Finality empowered Nightblade until it
has expired. The time remaining for refreshing is also increased with Tier 19 2
set bonus.

#### During Shadow Dance

- Shadowstrike
- Shuriken Storm, if there are >= 3 targets

#### Outside Shadow Dance

- Backstab, if you're about to cap on energy
- Shuriken Storm, if there are >= 3 targets

### Cool Downs

- Goremaw's Bite, if you're not in Shadow Dance or Stealth, you won't cap on
  combo points, and you have <= 50 energy
- Shadowblades, if you're not in Shadow Dance of Stealth

#### Stealth and Shadow Dance Priorities

If you want to abuse Flickering Shadows, you can use Sprint to Vanish if you are
safe from taking damage. This is definitely recommended if you have the Mantle
of the Master Assassin.

- If >= 1.5 seconds until capping energy
- If < 1.45 charges of Shadow Dance
- If Vanish is on cool down

It's recommended to use this macro to Sprint.

    #showtooltip
    /stopattack
    /cast Sprint

You should enter Stealth or Shadow Dance:

- If >= 60 energy
- If >= 5 targets
- If Vanish is on cool down and <= 1 charges of Shadow Dance
- If target will die in ~30 seconds or less

Abilities:

- Shadow Dance, if you have >= 2.45 charges
- Vanish
- Shadow Dance, if you have >= 2 charges, and <= 1 combo point
- Shadow Dance, if you have <= 1 combo point

#### Cleave

- Nightblade, if the target will live long enough
- Eviscerate, the priority target

## AddOns &amp; Macros

There isn't really any hard requirements for AddOns you should use. You should
look into using Weak Auras and/or an energy bar AddOn. I do not share the AddOns
that I specifically wrote myself for Subtlety Rogue as I get inundated with
people asking to add their feature, or fix a bug that doesn't affect me.

### Weak Auras

You can find a number of Weak Auras available on [wago.io](https://wago.io).
Below are links to the Weak Auras I use.

Shadow Dance charges are a separate Weak Aura to show them as a larger icon.

- Cool Downs [https://wago.io/4ycVDEaP-](https://wago.io/4ycVDEaP-)
- Shadow Dance [https://wago.io/V1QewusUG](https://wago.io/V1QewusUG)

Buffs/Debuffs includes pandemic highlighting for Nightblade and Symbols of
Death.

- Buffs/Debuffs [https://wago.io/VynJONTvZ](https://wago.io/VynJONTvZ)

Finality includes the percentage empowerment.

- Finality [https://wago.io/V1E9wy1bG](https://wago.io/V1E9wy1bG)

### Macros

There are a number of macros to help with Shadow Dance and abilities used with
it.

Shadow Dance &rarr; Shadowstrike

    #showtooltip
    /cast Shadow Dance
    /cast Shadowstrike

Shadow Dance &rarr; Shuriken Storm

    #showtooltip
    /cast Shadow Dance
    /cast Shuriken Storm

Shadow Dance &rarr; Symbols of Death &rarr; Shadowstrike

    #showtooltip
    /cast Shadow Dance
    /cast Symbols of Death
    /cast Shadowstrike

Shadow Dance &rarr; Symbols of Death &rarr; Shuriken Storm

    #showtooltip
    /cast Shadow Dance
    /cast Symbols of Death
    /cast Shuriken Storm

You can also create copies that use `/cast Vanish` instead of Shadow Dance.

Shadow Dance &rarr; Stealth &rarr; Potion

    #showtooltip
    /cast Shadow Dance
    /cast Stealth
    /use Potion of Prolonged Power

You can replace `Potion of Prolonged Power` with your potion of choice.

## Frequently Asked Questions

### How Does Finality Work?

Finality is pretty simple to understand once it's been explained.

When you use Eviscerate or Nightblade, if you do not have a Finality buff for
that finisher you will gain a Finality buff that will increase the damage of
the same finisher next time to use it.

The damage percentage of the buff depends on how many combo points were spent on
the finisher. It is 4% increased damage per combo point. So for a 5 combo point
finisher you would generate a 20% increased damage Finality buff, or if you're
talented into Deeper Stratagem and finish with 6 combo points you would generate
a 24% increased damage buff.

### Shadow Dance/Stealth Pre-Pull

There is a "bug"/"feature" where Stealth gets "protected" by Shadow Dance. This
means you can use Shadow Dance to delay Subterfuge from starting. The advantage
of this pre-pull is that you're able to start the encounter with Shadow Dance
up, which results in no loss of cool down reduction.

Due to recent changes you need to cast Shadow Dance before Stealth to abuse this
during a pull. You must keep in mind that you cannot cast Stealth if you are in
combat. So you have to make sure you use it prior to the actual pull. You need
to be **out of stealth** before using the macro.

## Summary

This guide is written to help those who want to start playing Subtlety Rogue or
get better at it. If you feel some part of the guide can be improved send an
email to [riffeu@gmail.com](mailto:riffeu@gmail.com) and explain what you feel
can be improved, and why.

Want to insult me and complain about how bad my guide is? Feel free to say so in
the **underbelly** channel on Ravenholdt Discord, but be aware you'll only be
wasting your own time. Stay angry.

Want to call me trash because I quit raiding mythic and how you're much better
than me? Congratulations you're great at a **video game**. I'm sure you'll go
far in life with that on your résumé. Stay humble.
