# How Stats Affect The Game
*Incrementality Matrix* is not a normal tabletop game. It's designed to scale up so much that ordinary dice would be basically useless.

As such, it has to have a different way of handling stats. You're gonna be doing a decent chunk of math, too, so buckle up.

## Anatomy of a Stat
Whether you're using a Basic Stat or a Derived Stat, there's a couple important terms that need to be established right away.

The number of--well, *numbers*--in your stat is called its *Scale*. For example, if you have a 1 in Viscosity, your Viscosity Scale is 1. If you had a *15* in Viscosity, your Viscosity Scale is 2. If you have a *200* in Viscosity, your Viscosity Scale is 3, and so on. For you math nerds, this is the exponent in Scientific Notation plus one.

The *first* number in your stat, from left to right, is called its *Simple Value*, or SV for short. For example, if you have a 15 in Viscosity, your Viscosity SV is 1 with a Scale of 2.

The *full number* is called the stat's *Full Value*, or FV. The Full Value of a stat should only really come into play as a tiebreaker or in special calculations.

## Figuring Out What Happens
When you want your character to do something that's dangerous--or something that may fail in a hilarious way that may or may not rhyme with past events--your GM will decide what the *difficulty* of the action is. For stuff like fighting bosses, this might be based on the stats of an NPC; for stuff like doing Weird Puzzle Shit or moving inanimate objects around, this might be a number the GM picked via the totally fair metric of whatever feels right. They'll then tell you which Stat applies.

To figure out what happens, compare the difficulty to whatever stat is applicable:
1. Compare your stat's *Scale* to the difficulty's Scale. If your stat's Scale is higher than the difficulty's Scale, you achieve godly success! You got what you wanted and then some, and you looked cool while doing it. If your stat's Scale is *lower* than the difficulty's Scale, things went horribly, horribly wrong because you're totally in over your head.
2. If the Scales match, compare your stat's *Simple Value* to the difficulty's SV. If your SV is higher than the difficulty's SV, you pulled off a regular, ordinary success. If your stat's SV is *lower* than the difficulty's SV, you screwed up, but not too badly.
3. If the Scales *and* the SVs match, you have to make a decision. You can still succeed, but it's at a cost--the GM will describe what you must sacrifice to win. If you really, genuinely cannot decide, compare the *Full Value* of your stat to the difficulty's Full Value. If *those* are tied, flip a coin; if heads, you win, if tails, you lose.

### Rolling Anyway
If you absolutely, positively *must* have some randomness in your life--or if you're in the early parts of the game and your stats are tiny--you can roll a d12 and add it to your stat before determining the results of an action. In the *really* early stages, this can let you punch above your weight class by upgrading you from Scale 1 to Scale 2. It stops being useful pretty quick, though.

## Tipping the Scales: Combos
You might have noticed that, since there's no dice to be rolled, the result of an action is 100% deterministic--either you have the stats to pull it off, or you don't. How do you pull off daring feats of heroism if you'll *always* lose to anything bigger than you?

This is where Combos come in. You can, as part of an action, tell the GM that you want to use the results as part of a *combo*. In addition, the GM can rule that whatever you did will create an immediate advantage, and make your action part of a combo anyway. If the action succeeds, you increase the party's current *Combo Multiplier* by 1. (It starts at 1, of course, so your first combo action would bring it to 2, another combo action would bring it to 3, and so on.)

When anyone in the party is resolving an action, they can--at any point in the process--declare that they're *consuming* the combo. When they do, the stat they're using for this action gets multiplied by the current Combo Multiplier, as everything involved in the combo comes crashing down into one long string of incredible coincidence that somehow makes everything work out better. Doing this *resets* the Combo Multiplier, so you can really only do it once per action, and you have to build up a new combo afterward. If you rolled a d12 and added it to your stat, that gets multiplied too.

## Were Making This Happen: Doing Things At The Same Time
Nobody said you had to wait for another player to finish their action before starting something! If your fellow players are having trouble, you may want to tell the GM that you want to help. Actions that are intended to help another player are called *Priority Interrupts*, or just Interrupts, and they are resolved *before* the action that you're trying to help with. You can theoretically create a massive chain of Interrupts by Interrupting the Interrupts, but it's recommended that you try to keep this within reason so that your GM doesn't go insane.

## Bringing It All Together
Here's an example of how an action might be resolved:
> John and his friends have just started playing SBURB, and John is struggling to deal with a group of Imps in his house.
> John's Classpect, *Heir* of *Breath*, gives him a Classpect Score equal to his Grit plus his Scamperway. John has 2 Grit and 1 Scamperway, so his Classpect Score is equal to 3.
> John's Strife Score is equal to 5 (2 Grit plus 3 Classpect Score). Regrettably, this Imp has a Strife Score of 10, making it too dangerous for John to fight effectively.
> John decides to roll a d12 to boost his attack, but--rotten luck!--he rolls a 2. 5 + 2 = 7, which isn't enough to bring him to the right Scale to take on this Imp.
> However, John's friend Rose has just enabled the house editing interface, and offers to Interrupt via editing John's house. Her Puzzle Score is 6 (3 Brainitude plus a Classpect Score of 3); she rolls a d12 to boost this, and gets another 6 for a total of 12. The GM informs her that she's found incredible success--by accident. She yanks a massive cast-iron bathtub off of its plumbing, which ends up perched precariously above the battlefield, creating a X2 Combo.
> John then consumes that X2 Combo--his panicked flailing is the straw that breaks the bathtub's back, sending it tipping over the edge of the roof and making it land on the Imp. Multiplying his 7 from earlier by 2 from the combo, he gets a 14, which means he can win at a cost; John, Rose, and the GM all agree that the destruction of that beautiful cast-iron bathtub is a terrible cost indeed, but a worthy sacrifice in the name of victory.

# The Basic Stats

Your character has a set of *Prime Attribulations*. Normal people call them *Basic Stats*. There are six in total, representing different ways of solving problems:

- Grit: Lifting stuff, hitting things really hard, and being SO STRONG. If you solve things by stomping on them, this is your favorite stat.
- Viscosity: Being hard to hurt, let alone kill. If you solve things by grinning and bearing it, this is for you.
- Moxie: Being a clever fox, playing tricks and pranks and other shenanigans. If you solve things with dumb puns, this is the stat you want.
- Scamperway: Being fast, being precise, and being done before anybody notices. If you solve things with perfect aim, you need this stat.
- Brainitude: Knowing a lot. Like, a LOT a lot. Expanding brains go here. If you solve things by knowing a bit of trivia, this is where it comes from.
- Pulchritude: Being the smoothest dude and/or dudette in the world. If you solve things by making a good first impression, this stat's got your back.

Each of these stats can factor into your *Factored Attribulations*--or, as people who need to get things done might call them, your *Derived Stats*.

# The Derived Stats

Derived Stats are calculated by adding other stats together.

## Classpect Score
Your Classpect Score is the sum of your Class's Primary Attribute and your Aspect's Primary Attribute, and it contributes to a lot of different things. Basically, if you build up the stats that are core to your classpect, you get a buff to almost everything else as a reward. Check out the Classpects chapter for details on each Class and Aspect.

For example, if you're the Seer (Brainitude) of Light (Scamperway), your Classpect Score is your Brainitude plus your Scamperway.

Note that until you Enter the Medium, you don't technically have a Classpect yet, so you don't get a Classpect Score. (See the chapter on Act 0 for more information on how you generate your characters.)

Whenever you want to do something cool, and it's not covered by another Derived Stat, you can use your Classpect Score instead. However, it has to be sufficiently cool! It needs to either be something heroic and awesome, or something that's in line with what your Classpect would do. You can't just use your Classpect to, like, open a jar of pickles or something. You need to be doing things that are worth telling stories about.

The GM may rule that your action does not befit your Classpect or your status as a Player; if that happens, you're stuck using base stats, which is way less powerful.

## Strife Score
Your Strife Score measures your ability to kick ass and take names; you can lean on it whenever you need to go punch something.

Strife Score has a special function: you gain Grist equal to your Strife Score whenever your party decides to Grind (more on that in the Grinding chapter).

Your Strife Score is calculated by your Grit plus your Classpect Score.

## Vial Score
Your Vial Score measures your ability to take hits and keep going; it governs the effects that incoming threats have on you.

Your Vial Score is calculated by your Viscosity plus your Classpect Score.

## Puzzle Score
Your Puzzle Score measures your ability to put up with Weird Puzzle Shit, including the needlessly-confusing and overly complex interface of SBURB. You can even use it in place of your Strife Score if you can come up with a suitably puzzly way to defeat an enemy.

Your Puzzle Score is calculated by your Brainitude plus your Classpect Score.

## Abilitech Score
Your Abilitech Score measures your ability to manifest and wield your Aspect. Essentially, whenever you want to do something magical with your Class and Aspect, you use this.

Your Abilitech Score is calculated by your Moxie plus your Classpect Score.

## Reactivity Score
Your Reactivity Score measures your ability to get to things quickly or react before other people do. If you're trying to do something faster than someone else, your Reactivity Score is what applies.

Your Reactivity Score is calculated by your Scamperway plus your Classpect Score.

## Chutzpah Score
Your Chutzpah Score measures the cut of your jib, and how much other people like it. If you want to convince people you're a hero, this is how.

Your Chutzpah Score is calculated by your Pulchritude plus your Classpect Score.

## Gambit Score
Your Gambit Score is special; you decide what it's for. Maybe your character is particularly fond of practical jokes, and thus has a *Prankster's Gambit*. Maybe you're prone to doing a somersault off the nearest door-latch when things get a little too heated, so you have a *Chillaxification Gambit*. Maybe you enjoy the occult a bit too much, so your Gambit is a *Sanatos Gambit*.

Whatever the case may be, the Gambit Score is a unique thing that your character is particularly good at or prone to doing. It's especially useful because you get to pick *TWO* Basic Stats to add to it, meaning that you can improve it steadily while spreading your stat points across more than one thing. Make sure you also write down *what your Gambit applies to*, because that's unique too.

Your Gambit Score is calculated by your Classpect Score plus both Basic Stats you picked for it.

# Increasing your Stats
At character creation, you get three points to distribute across your six base stats. Regular, boring, ordinary people aren't exactly mighty champions, after all.

However, over time you'll get to improve your base stats. Specifically, *ascending your Echeladder* grants you *Stat Points* (see the Echeladder chapter for more info about Echeladders). Each Rung you Ascend to grants 3 Stat Points. Each Stat Point can be spent to increase a Stat, 1-for-1.

If you ascend multiple Rungs at once (which will probably happen at some point), you gain Stat Points for each one you ascended through. In other words, if you ascend 3 Rungs at the same time, you get a total of 9 Stat Points, 3 for each Rung you ascended.

You can spend the Stat Points whenever you're not in immediate danger. In most circumstances, you can use the stat points as soon as you get them, but you're not allowed to interrupt a fight just to spend stat points that you got by doing something cool.