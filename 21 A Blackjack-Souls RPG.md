# **21** *A Blackjack-Souls RPG*

[TOC]



## Deals

The primary mechanic is a **Deal**, which is played as one hand of blackjack. 

- The goal of a Deal is to beat the value of your opponent's hand (or a static number) without Busting (exceeding 21)
- Face Cards are worth 10. Aces can be worth either 1 or 11, whichever makes a better hand.
- Each player starts with two cards. Players take turns, choosing to either 'Hit' (draw another card) or 'Stand' (hold your total and end your turn)
- If a player goes over 21, they Bust and automatically fail the Deal

When performing a task of arbitrary difficulty, you must meet a Target Number (such as 15, 18, or 21) without Busting.

When in direct contest with another, you Deal against eachother. The player with higher value (without Busting, or exceeding 21) succeeds. Equal values indicate a clash of fully equal skill.

If either player draws a Joker, the joker is worth '0' and the deal becomes 'Critical'. A winner has some spectacular swing of skill or fate give them an advantage, and the loser has some disabling misfortune (as determined by the GM)

## Damage

When attacking a target, you pit one of your abilities against your target. If an attacker wins a Deal, the defender places all of the cards they played during that deal into their **Damage Pile**. A player can only take 8 cards in their Damage Pile before being Incapacitated.

When the Defender wins, if they are able to Retaliate (such as both being armed in melee combat), then instead the attacker takes all the cards they played into their Damage Pile.

In case of a draw, neither player is damaged.

## Conflict

On entering a conflict, each player chooses a Card to represent themselves. Those cards are shuffled together and dealt out to determine what order they act in. When a player acts, move their card to the bottom of a pile.

On a character's turn, they can be considered to Move and then Act. The GM is the final rule on how fast and far a character can move on their turn. Acting (including any action that leads to a deal) ends your turn. Turns should be succinct whenever possible, and almost never involve more than one Deal.

### Delay

Some actions involve a 'Delay'. During a Delay, a character begins their task, and then a certain number of other characters take their turn (equal to the delay) before their turn is completed. If a character is damaged during this time, the action fails.

 *Delay skills are far more effective in larger fights, or fights where allies can cover for you. They are less effective in 1-on-1 conflicts where your opponent can focus only on you*

## Stats

There are 6 Stats, divided into 3 Groups:

- Strength / Dexterity
- Endurance / Hope
- Wits / Power

When making a Deal, you will test one or more of these skills. You gain **Edge** on that deal equal to the highest applicable skill.

When creating a character, first choose one stat grouping. Gain +1 in both of those stats. Then choose two different individual stats and gain +1 in each of them. For every point in a stat, you may choose an Edge Skill for that stat.

## Edge Skills

During a Deal, each character will have **Edge** equal to their highest Skill *(with a bonus or penalty based on circumstances)*, which can be used on Skills. **Edge Skills** cost Edge, and each skill can only be used once during a deal.

All characters have access to 3 Universal Edge Skills. In addition, players gain edge skills related to their Stats - one skill per point in a stat. Additional Edge Skills can be gained with certain equipment, spells, or other effects.

### Universal Skills

| Skill         | Cost | Effect                                                   |
| ------------- | ---- | -------------------------------------------------------- |
| **Influence** | E1   | Make any one individual card worth +1 or -1              |
| **Soul**      | E2   | Before Busting, Nullify (reduce to 0) one of your cards  |
| **Humanity**  | E3   | Change the value of any one Face Card to between 1 and 5 |

### Strength Skills

| Skill            | Cost | Effect                                             |
| ---------------- | ---- | -------------------------------------------------- |
| **Overbear**     | E2   | All parties draw a card                            |
| **Weightlift**   | ---  | You may hold an extra point of Weight in each hand |
| **Power Strike** | ---  | Delay 1; Deal +1 Damage with a Weapon              |

### Dexterity Skills

| Skill        | Cost | Effect                                                       |
| ------------ | ---- | ------------------------------------------------------------ |
| **Riposte**  | E1   | If your opponent Busts, they draw an additional card         |
| **Critical** | E2   | If you hit 21 exactly, your opponent draws two cards         |
| **Flanking** | ---  | If you attack a target who has not yet attacked you, target can't Retaliate |

### Endurance Skills

| Skill          | Cost | Effect                                                       |
| -------------- | ---- | ------------------------------------------------------------ |
| **Sturdy**     | E2   | All of your cards are worth 1 less                           |
| **Recompense** | E3   | Instead of drawing from your deck, draw a specific card from your Damage Pile |
| **Vitality**   | ---  | You can take 10 cards in your Damage Pile before being Incapacitated |

### Hope Skills

| Skill        | Cost | Effect                                                 |
| ------------ | ---- | ------------------------------------------------------ |
| **Light**    | E1   | Make one of your cards worth +1 or -1                  |
| **Guidance** | E2   | Play this deal with the top card of your deck revealed |
| **Optimism** | ---  | Edge+1 on all Non-Combat deals                         |

### Wit Skills

| Skill          | Cost | Effect                                                       |
| -------------- | ---- | ------------------------------------------------------------ |
| **Lucky Lady** | E0   | Make any one Queen worth 2                                   |
| **Lucky Lad**  | E0   | Make any one Jack worth 2                                    |
| **Cheek**      | E2   | On any opposed roll where you would not take Damage (including social/stealth rolls), discard up to 2 non-face cards |

### Power Skills

| Skill            | Cost | Effect                                                       |
| ---------------- | ---- | ------------------------------------------------------------ |
| **Power Spell**  | E2   | When casting a spell, target draws 2 additional cards if they take damage |
| **Aura**         | E2   | Switch the value of the first card you drew with the first card your opponent drew |
| **Expert Spell** | ---  | You may reduce the Delay of a spell, reducing your Edge on that spell by twice that amount. |

---

## Magic

There are three types of Magic available: **Miracles, Sorcery,** and **Pyromancy**. Spells (when used during an Encounter) generally involve a Delay and a Skill Test in order to use.

- **Miracles** are based on Hope and Power, and mostly include healing and support abilities. Miracles require a Talisman in one hand to activate.
- **Sorceries** are based on Wit and Power. They are broad and varied, including damage and utility skills. Sorceries require a Catalyst in one hand to activate.
- **Pyromancies** are based on Endurance and Power. They are primarily destructive and often dangerous to casters and allies. Pyromancy requires a Pyromancy Flame in one hand to use.

### Miracles

Miracles are based on Hope and Power, and require a Talisman in one hand to activate. A character may learn a number of Miracles equal to their **Hope**.

| Miracle           | Delay |    Deal    | Effect                                                       |
| ----------------- | :---: | :--------: | ------------------------------------------------------------ |
| **Heal**          |   2   |  Hp/Pw 15  | Remove either all Face or Non-Face Cards from your Damage Pile |
| **Group Heal**    |   3   |  Hp/Pw 17  | Choose a suit; remove all cards of that suit from all player's damage piles |
| **Great Heal**    |   4   |  Hope 20   | Remove all cards from the Damage Piles of yourself and all others within arms reach |
| **Force**         |   0   | Pow vs End | Stun and throw backwards nearby targets. Allies gain E+1. *Stunned targets can't retaliate and have E-2 until the end of their turn* |
| **Tranquil Walk** |   2   |  Hp/Pw 17  | For 30 Seconds (~3 Turns), all nearby targets have Dexterity and movement speed halved (rounded down) |

### Sorcery

Sorceries are based on Wits and Power, and require a Catalyst in one hand to activate. A character may learn a number of Miracles equal to their **Wits+1**

| Sorcery          | Delay |    Deal    | Effect                                                       |
| ---------------- | :---: | :--------: | ------------------------------------------------------------ |
| **Soul Arrow**   |   1   | Pow vs Dex | A ranged magic attack which can be fired at any target in line of sight. Allows retaliation against Ranged Attacks |
| **Magic Weapon** |   2   |  Wt/Pw 17  | For one conflcit, gain Edge+1 when Attacking/Defending with a Weapon |
| **Magic Shield** |   2   |  Wt/Pw 17  | For one conflict, when using a Shield you gain an Edge Skill: **E2 - Take No Damage** |
| **Hush**         |   2   |  Wits 17   | For one conflict, you emit no sound. Edge+2 when evading detection. |
| **Demon Prank**  |   0   |  Wits 15   | Make a loud, distracting noise at a location you see. Unaware targets with 1 or less Endure are Stunned. Unaware targets with 1 or less Wits are distracted. |
| **Light**        |   2   |  Pw/Wt 12  | Create a floating light that follows you for one conflict.   |
| **Fall Control** |   3   |  Wits 17   | For one conflict, you may fall exceptional (otherwise survivable) distances silently and without injury. |

### Pyromancy

Pyromancies are based on Endurance and Power, and require a Pyromancy Flame in one hand to use. Pyromancers start with **Combustion,** then learn a number of Pyromancies equal to the lowest of their **Endure/Power**

| Pyromancy        | Delay |      Deal      | Effect                                                       |
| ---------------- | :---: | :------------: | ------------------------------------------------------------ |
| **Combustion**   |   0   | Pw/En vs Dx/En | Create a burst of flame from your hand, damaging everything within arms reach of you. If you fail (even without retaliation), take half of your cards dealt as Damage |
| **Fireball**     |   2   |   Pow vs Dex   | Lob a ball of liquid fire at a location up to 20' away. The fireball hits anything within arms reach of its target. |
| **Firestorm**    |   4   |   Pw vs Dx-1   | Flame erupts from the ground, damaging everything within 20' |
| **Power Within** |   2   |    Pw/En 17    | For one conflict, gain Edge+1 on all deals, but add 1 card to your Damage Pile after each deal |
| **Flash Sweat**  |   2   |     En 16      | For one conflict, take half damage from Fire, and gain Edge+1 when Defending against Fire |

---

## Items / Equipment

A person can hold a limited amount of weight, based on their Endurance.

- Each hand can hold equipment with weight equal to Endure+1
- Equipment can be held in 2 hands to double the amount of weight you can hold
- Equipment can be held in reserve for each hand if you have extra Weight to spare. Switching to a reserve item adds 1 Delay
- Armor can have weight up to Endure+1
- Armor can hold a number of extra items, which can be drawn into your hand and used with Delay 1

### Melee Weapons

| Weapon         | wgt  |  Stat   | effect                                                       |
| -------------- | :--: | :-----: | ------------------------------------------------------------ |
| **Dagger**     |  0   |   Dex   | ***While Defending***: Edge-1; if you draw 2+ Face Cards, your  opponent draws a card |
| **Rapier**     |  0   |   Dex   | ***While Defending***: you may use an Edge Skill more than once |
| **Scimitar**   |  0   |   Dex   | You may move after attacking                                 |
| **Shortsword** |  0   | Str/Dex | ***While Attacking:*** E1: Subtract 1 from any card          |
| **Broadsword** |  1   | Str/Dex | E1- Add 2 to a card                                          |
| **Mace**       |  1   |   Str   | If you draw Clubs, damaged targets are Stunned<br> *Stun: can't retaliate; E-2 until end of their turn* |
| **Spear**      |  2   | Str/Dex | You can attack at short distances; if you do, target can't Retaliate |
| **Battleaxe**  |  2   |   Str   | Can't Retaliate. ***When Attacking:*** Edge+1, target takes +1 Damage if they fail |
| **Greatsword** |  4   |   Str   | Can't Retaliate. Delay 1 to gain Edge+2 and attack multiple nearby targets at once. |

### Ranged Weapons

| Weapon       | Wgt  | Skill | Effect                                                       |
| ------------ | :--: | :---: | ------------------------------------------------------------ |
| **Shortbow** |  1   |  Dex  | Requires two hands; Delay 1 to atttack at range. Allows retaliation against ranged attacks. |
| **Longbow**  |  2   |  Dex  | Requires two hands; Delay 2 to attack at a range with Edge+1. Allows retaliation against Ranged Attacks. |
| **Crossbow** |  2   | Dx/Wt | Delay 2 to attack at range. Allows retaliation against ranged attacks. |

### Shields

| Shield          | Wgt  | Skill | Effect                                                       |
| --------------- | :--: | :---: | ------------------------------------------------------------ |
| **Buckler**     |  0   |  Dex  | ***While Defending:*** E1-Subtract 2 from an opponent's card |
| **Kite Shield** |  1   | St/Dx | When taking damage, discard any Clubs                        |
| **Greatshield** |  2   |  End  | If you Bust while defending, ignore 2 damage                 |

### Spell Tools

| Tool                | Wgt  | Effect                        |
| ------------------- | :--: | ----------------------------- |
| **Talisman**        |  0   | Allows casting of Miracles    |
| **Pyromancy Flame** |  0   | Allows casting of Pyromancies |
| **Catalyst**        |  1   | Allows casting of Sorceries   |

### Armor

| Armor               | Wgt  | Pockets | Effect                                                       |
| ------------------- | ---- | ------- | ------------------------------------------------------------ |
| **Explorer's Gear** | 1    | 3 Items | Swapping and using items does not require a Delay            |
| Shadow Gear         | 1    | 1 Item  | Edge+1 when Defending with Dexterity                         |
| **Leather Armor**   | 2    | 2 Items | Your Damage Pile can hold 2 more cards                       |
| Chainmail           | 3    | 1 Item  | Your Damage Pile can hold 4 more cards                       |
| **Platemail**       | 4    | 1 Item  | Your Damage Pile can hold 4 more cards. You take 1 less card of damage. |

### Items

| Item                | Stack | Effect                                                       |
| ------------------- | :---: | ------------------------------------------------------------ |
| Crescent Moon Grass |  10   | Remove one card from your Damage Pile                        |
| **Half Moon Grass** |   5   | Remove either all Face Cards or Non-Face Cards from your Damage Pile |
| **Throwing Knife**  |   5   | Attack with Dex/Wit at range. While in hand, allow retaliation against ranged attacks |
| **Firebomb**        |   3   | Attack with Str/Wit at range. All enemies within arms reach of target are hit. |
| **Turpentine**      |   2   | For one encounter, your melee weapon attacks cause opponents to draw +1 Card when damaged. |

## Creating a Character

- Choose and write down your Stats:
  - Choose one Stat Group (Str/Dex, End/Hop, Wit/Pow) and gain +1 to both
  - Give +1 to two individual stats; you should have no more than +3 in any one stat
- Choose and learn Edge Skills- for each point in a Stat, choose 1 Edge Skill related to that stat. You should have 4 total, in addition to the 3 Universal Skills. Write them down.
- If you have any points in Power, Hope, or Wits, you may learn Spells. You can only cast them with a matching Spell Tool in hand. You may write these down if you intend to start with a Spell Tool, or leave them blank for later.
  - You can learn Miracles equal to your Hope
  - If you have Wits, you can learn Sorceries equal to your Wits+1
  - If you have Power or Endurance, you learn the spell **Combustion**, plus Pyromancies equal to the lowest of your Power/Endure
- Choose your starting Equipment and Armor
  - Your Left and Right Hands can each hold weight equal to your Endurance+1. Items twice that heavy can be used with both hands.
  - If you have additional weight left over, each hand can have one piece of Reserve Equipment
  - You may choose a set of Armor; your Armor can weigh at most equal to your Endurance+1
- Choose any starting Items
  - Choose a number of starting items based on the number of Pockets in your Armor. The 'Stack' is how many of the same item you start with, and how many fit in one pocket. You may choose the same item multiple times to carry extras.
  - Incidental Items (rope, trinkets, etc) equal to your number of Pockets can be carried, plus one for any extra Weight leftover between hands.