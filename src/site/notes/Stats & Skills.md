---
{"dg-publish":true,"permalink":"/stats-and-skills/"}
---

# Stats
 *some stats have related sub-stats or resources*
 
 **Mind** - the measure of capacity for intelligence  
 - [[Lore Slots\|Lore Slots]] -  an abstract measure of theoretical information possessed by the character.
 
 **Social** - a definition of one's general ability to perform in social situations

 **Spirit** - a representation of passion and character 
- [[Mana\|Mana]] - the energy used for casting spells and using magic. 

 **Body** - an estimate of one's raw physical capabilities and health  
- [[Health\|Health]] - a resource describing how many debilitating conditions a character can suffer before collapsing.
- [[Inventory Slots\|Inventory Slots]] - factor that shows potential inventory space of a character.

 **Control** - an approximation of one's control over their movements
- [[Evasion\|Evasion]] - the ability to avoid attacks and similar.
# Skills:

**Main Modifier** is simply equal to a stat's or skill's rating, 
**Sub Modifier** is that rating divided by 10 rounded down.

*Stats and Skill ratings cannot go below 0.*

Main Modifier may be shortened to MM and Sub Modifier to SM.

You must develop a Skill to benefit from Sub Modifiers, otherwise only add the Main Modifier.  
If a Skill has more than one Sub Modifier or Main Modifier you can choose only one to benefit from. 

If a SM of a Skill is another Skill that you do not have the bonus of that SM is equal to 0.
You cannot acquire a Skill if it's MM is another Skill you don't already have.

| Skill                           | Main Modifier   | Sub Modifier   |
| ------------------------------- | --------------- | -------------- |
| Acrobatics                      | Control         | Body           |
| Acting                          | Control         | Social         |
| Animal Handling                 | Spirit          | Insight        |
| Art                             | Spirit          | Social         |
| Athletics                       | Body            | Control        |
| Barter                          | Social          | Mind           |
| Boating                         | Body            | Perception     |
| Climbing<sup>2</sup>            | Athletics       | Acrobatics     |
| Deception                       | Social          | Mind           |
| Disguise<sup>2</sup>            | Acting          | Deception      |
| Insight                         | Social          | Perception     |
| Intimidation                    | Body            | Acting, Spirit |
| Investigation                   | Mind            | Perception     |
| Lockpicking                     | Control         | Perception     |
| Navigation                      | Perception      | Mind           |
| Perception                      | Mind            | Body           |
| Persuasion                      | Social          | Insight        |
| Pickpocketing                   | Control         | Insight        |
| Riding<sup>2</sup>              | Animal Handling | Control, Body  |
| Seduction<sup>2</sup>           | Acting          | Insight        |
| Speech                          | Spirit          | Social         |
| Stalking<sup>2</sup>            | Stealth         | Tracking       |
| Stealth                         | Control         | Perception     |
| Tracking<sup>2</sup>            | Perception      | Mind           |
| [[Spells#Spellwork\|Spellwork]] | Mind            | Spirit         |

This is a list of example Skills more can be created when needed. For example if a Player wants their character to be specifically good at dancing a Dancing skill with Art as Main Modifier and Acrobatics as a Sub Modifier can be created easily with the GM's help. 

Similarly an alternative Sub Modifier or a Main Modifier may be added to a skill. Example: A player may argue the Interrogation skill could use a Torture Skill and not Insight as Main Modifier.

Special Cases can also be argued for, if a character has the ability to feel emotions magically the Main Modifier of Insight may be changed from Social to Spirit if the GM agrees.

The higher the [[Skill Order\|order]] of a Skill the more powerful it can be, for example Seduction has Acting as it's Main Modifier and Insight as it's Sub Modifier, both of these are skills which already gained the benefits of other Sub Modifiers in this case calculating the entire tree of this skill assuming all relevant Stats scores are at 28 would look like this:
```
Perception = MM Mind: 28 + SM Body: 2 (28/10↓[^1]) = 30.
Insight = MM Social: 28 + SM Perception: 3 = 31.
Acting = MM Control: 28 + SM Social: 2 = 31.
Seduction = MM Acting: 31 + SM Insight: 3 = 34.
```
This results in a score that is higher than any [[Skill Order#Skill Root\|Skill Root]] by 6.

### Developing a Skill

While base Stats are hard to increase Skills can easily be trained in two main ways. The most common way is via failing a roll, when a character fails a skill check involving a Skill they may attempt an **advancement roll**. To do this a Player will roll a 1d100 and if their roll is higher than the target score the Skill gains an **isolated bonus** (meaning excluded from all calculations regarding other Skills) based on a following 1d4 throw called a **study roll**.
To learn a Target score for your Skill rating consult this table:

| Rating     | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 10  | 11  | 12  | 13  | 14  | 15  | 16  | 17  | 18  | 19  | 20  | 21  | 22  | 23  | 24  | 25  | 26  | 27  | 28  | 29  | 30  | 31  | 32  | 33  | 34  | 35  | 36  | 37  | 38  | 39  | 40  | 41  | 42  | 43  | 44  | 45  | 46  | 47  | 48  | 49  | 50  | 51  | 52  | 53  | 54  | 55  | 56  | 57  | 58  | 59  | 60  | 61  | 62  | 63  | 64  | 65  | 66  | 67  | 68  | 69  | 70  | 71  | 72  | 73  | 74  | 75  | 76  | 77  | 78  | 79  | 80  | 81  | 82  | 83  | 84  | 85  | 86  | 87  | 88  | 89  | 90  | 91  | 92  | 93  | 94  | 95  | 96  | 97  | 98  | 99  | 100 |
| ---------- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **Target** | 98  | 98  | 98  | 97  | 97  | 97  | 96  | 96  | 96  | 95  | 95  | 95  | 94  | 94  | 93  | 93  | 92  | 92  | 91  | 90  | 89  | 88  | 87  | 86  | 84  | 82  | 80  | 78  | 76  | 75  | 73  | 71  | 69  | 66  | 63  | 60  | 57  | 54  | 51  | 50  | 47  | 44  | 41  | 38  | 35  | 32  | 29  | 26  | 23  | 20  | 23  | 26  | 29  | 32  | 35  | 38  | 41  | 44  | 47  | 50  | 51  | 54  | 57  | 60  | 63  | 66  | 69  | 71  | 73  | 75  | 76  | 78  | 80  | 82  | 84  | 86  | 87  | 88  | 89  | 90  | 91  | 92  | 92  | 93  | 93  | 94  | 94  | 95  | 95  | 95  | 96  | 96  | 96  | 97  | 97  | 97  | 98  | 98  | 98  | -   |

**Rating** row is the Skill score of an applicable Skill (including any score advancement already achieved and any other bonuses unless otherwise stated).

**Target** row indicates the number you must roll higher than to succeed on an advancement roll.

**Study Roll** is done once you succeed on an advancement roll, unmodified this roll is a simple 1d4, the result is added to a relevant Skill rating.

### Specializing a Skill

Specializing is an optional feature that may slightly boost the effectiveness of a character. 
During an occasion where a character has the option of learning a new skill they may instead try to develop one of their existing skills into a more specialized form, for example Urban Climbing is a specialized form of Climbing for the urban environment. Urban Climbing has the same MM and SM as normal Climbing but it additionally benefits from the SM of it's *MM*. Example:
```
Climbing = MM Athelthics: 30 + SM Acrobatics: 2 = 32
Urban Climbing = MM Athelthics: 30 + SM Acrobatics: 2 + SM Athelthics: 3 = 35
```
The character still has access to the original Climbing Skill but in urban environments they benefit from the specialized version as such the only cost of specializing is losing the opportunity to acquire an entirely new skill.

[^1]: This sign means the result of a calculation is rounded down.
