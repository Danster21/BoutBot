# BoutBot
My Reddit robot for, hopefully, a reinvigorated Chroma
----------------
# Introduction (The long boring, story drivin one. More of a foreward)
<p>So, this is a long time coming. On December 2nd, 2015 I submitted my idea for a new play style in /r/councilofkarma. It was after we had been talking about replacing the current battle system because it was too confusing and people weren't joining. I mean, that's the reason we as a whole were talking about it; not to sound too salty, but Orangereds were talking about it for a while because we were losing a lot with no end in sight. Regardless, this method received a very positive reception from my OR peers and generally positive reception from the group as a whole. However, nothing really changed and the Council went in a different direction. The current method is based off another suggestion I had, but I'm not satisfied with that. 
<br></br>My real problem was that reostra was too nice, and no way could I eevr demand so much from someone who continually just gives and gives and gives. I knew what I had to do, I had to make my own. It also means that I can have practical knowledge on python. The other obvious benefit is that it gives me free reign to make changes as I see fit. Most changes will be like my sports subreddit CSS, fixing my own mistakes. Hopefully it turns into more of my chroma subreddit CSS, adding things, pouring my free time into a passion project. I give myself about a 5% chance that this turns into a passion project, 50% chance that I work on this for a week and then let it sit on my bookmarks bar for months, making no progress. Afterall, it's much easier to come up with ideas than it is to come up with lines of code (those which will work). 
<br></br>Either way, this will be a fun experience. You can only go into something completely blind once.</p>

________

# Plan
          75/110                                                      54/100
           ____                                                         ____
         /       \                                                    /       \
        |         |                                                  |         |
         \ ____  /      _                                      _      \ ____  /   
             |       __| |______________        ______________| |__       |
             |______|__| |_____________/        \_____________| |__|______|
            /|         |_|                                    |_|         |\   
           / |                                                            | \
          /  |                                                            |  \
         /   |                                                            |   \
        /    |                                                            |    \
            / \                                                          / \
           /   \                                                        /   \
          /     \                                                      /     \
         /       \                                                    /       \
        /         \                                                  /         \

_______

      | DEF: XX | ATK: XX |                                      | DEF: XX | ATK: XX |
      | SPD: XX | EXP: XX |                                      | SPD: XX | EXP: XX |
      | Orangered  lvl. 1 |                                      | Periwinkle lvl. 1 |             

_______

>>>>> **Orangered** uses Medium Attack, **it misses!**

>>>>> **Periwinkle** uses Light Attack, **it deals 7 damage!**

>>>> **Orangered** uses Medium Attack, **it deals 15 damage!**

>>>> **Periwinkle** uses Heavy Attack, **it misses!**

>>> **Orangered** uses Light Attack, **it deals 5 damage!**

>>> **Periwinkle** uses Heavy Attack, ***it deals 25 damage!!!***

>>**Orangered** uses Medium Attack, *Critical Hit!* **It deals 19 damage!**

>> **Periwinkle** uses light Attack, **it deals 3 damage!**

> **Orangered** uses Light Attack, **it deals 7 damage!**

> **Periwinkle** uses Heavy Attack, **it misses!**

That above is an example of what could be displayed for one battle, which would take place in a comment thread similar to what we use now, but allow me to elaborate:

So the idea is that we battle like normal, one team invades and a battle is started in /r/FieldOfKarmicGlory and there is 24 hours before it begins. Then people are allowed to sign up for battle, they lead like normal but it takes a lot quicker because it's just one person (Think 10 minutes between territories (And of course, this idea is expanded upon in the "Tax" section)) but once you're there you sign up for battle and you are slated in a tournament style joust, called a bout. This is a dual headed one with Peris on one side and Orangereds on the other. There will be people who battle right off the bat and people who may have to wait a battle before their competitor is chosen (like how a bye week works in sports playoffs). This means it's Orangereds facing other Orangereds and same with the Periwinkles. This goes on until there is a champion of both sides and they duke it off in a championship for control of the territory. Losers will be placed in a losers pool, where they will be randomly matched up with the other losers to play as long as the tournament endures. Players will get kicked from the losers pool if they neglect to make any moves (so assuming they're afk)

Battles take place between people and they each start off with 100% health (Although, this may change if I add in potions for midrounds). You have a choice of Strong attack (Deals most damage, has the least accuracy (I'm thinking 18-25 damage, 25-30% accuracy), Medium attacks (Maybe 10-17 damage, 40-60% accuracy) and light attacks (probably 4-9 damage, 70-80% accuracy). Each person has 3 minutes (or whatever makes the most sense, might end up being 1 tick) to put in their command, if it doesn't go off, you automatically use a medium attack (perhaps a default attack that the person can set pre-battle). Once your opponent is all the way dead, you wait until your next competitor (Or probably the whole first portion of battles) have been decided. 

That's just the general basis of it, the logistics are more intricate. Some ideas I've been considering are that each person has 4 slots for armor and 3 extra clothing items they can carry with them in their inventory. These items are Helm, Chestplate, Weapon and Footwear. Helms are all about critical hit chance and will decrease your opponents chance for them. Chest plates are about defense and will decrease your opponents attack power. Weapons are naturally about attack and will boost you there (sometimes at a cost to speed) and footwear is all about speed (Sometimes at a cost to defense).

Levels and experience are all about tiers, items have tiers and you can only get items that are in your tier. Once you level up, you have access to a new tier, which encourages people to fight. Experience is doled out at a base of 35 EXP with bonuses to the level of closeness you get to the championship battle (so people with more people battling won't get more experience because they had more people to kill). Items in tier 1 are basic, only buff one stat (so like +1 DEF or +3 ATK) but later tiers have special effects (like you always go first to start the battle, but you alternate going first with your enemy, or poison effects or you will always hang on to 1 HP) and those effects will last up until the final battle, where it's all vanilla and a 1-on-1 to the death.

You can only carry 3 items at a time, along with your 4 equipped items. This is to prevent people from keeping their best armor in 4 unused slots and their weakest (or no other armor) in all other 4. If someone wanted to throw the battle, they could just tell certain people to equip their weakest armor, but if you wanted to do that with only 3 slots, you would have to sacrifice one of your best pieces of armor. Otherwise I'd let people have lots more slots. So if anyone could find a way to prevent this, then I'm all ears.

A system I'm considering is a gold system. After a battle, if you win, you get gold (could be Chromanium, or whatever it's called, but for our purposes here, it'll be called gold). After you win, you can use any gold you've accumulated to purchase items to heal yourself more, or perhaps give yourself a buff. 


That's the gist of it, there's probably more to it that I've forgotten to mention, I've done a lot of thinking on this and the intricacies of it. If you have any questions, please feel free to ask!

_________________

[Stems off this posted from eons ago](https://www.reddit.com/r/councilofkarma/comments/2k96il/season_3_ideas_and_discussion/clj6sjn)

_________________

Suggestions from others:

## Ghtuy: 

Idea: only face off members of the same team until the number of entrants is the same on both sides. Then, pair people with the opposite team. If only one team remains at a certain stage of the bracket, then that team wins and you don't have to go all the way to the final. Like, if the 4 battlers in the semifinal are all orangered, then orangered wins the battle.

## Fate:

(First one)

Dude. This is awesome. Battlers could enter the field and get paired up against an unoccupied opponent and battle. When the battle is over, they get paired up against some other battler. This goes on for an hour and then the team that wins more skirmishes wins!

(Second)
 
My mind is exploding right now with the possibilities. You could do

&gt; attack danster21

and pick a fight. Or just say 

&gt; attack

to pick a random fight.

If you're unoccupied, you can say 

&gt; support danster21

and provide a boost.

this could be so epic!

(Third)

Each skirmish could be limited to 10 minutes and each back-and-forth could be capped to 1 minute. If you don't respond in 1 minute, opponent can make a second move and so on! OMG. I am losing it. HALP!!!

## Weebs:

&gt; Each person has 3 minutes to put in their command

Oy! You mean for the first command in case they walked away from the computer while waiting for a partner? Other than that sounding like it could make me impatient, I really like the idea of one-on-one dueling. It would be a refreshing change for Chroma and it would make battles much less tedious.

_______

_______

Obviously it's a work in progress. I hardly know Python but I'm committed to learning it. Most of this stuff would come down to the capabilities of the bot and what it could handle. I think if we put chroma's brightest minds together in January or so (Particularly so I'll have time to learn and Fate will be less busy) we could really possibly crank it out. Again, if you have any comments or concerns, please comment below so we can have a civil discussion about them.
