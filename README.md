## _Slow Productivity_
Cal Newport

> \[Slow productivity\] requires that you free yourself from the constraints of the small so that you can invest more meaningfully in the big.

### Autopilot
* Same place, same time, work on things even if they're not the most urgent. 
* Leverage rituals. 

### Synchronize
Separate the work from the conversations surrounding it. 

* If you're talking about work more than doing the work (especially asynchronously, like with e-mail), solve this with "office hours": 30-60 minutes every afternoon, always available, door open, to chat about relevant issues.
* docket-cleaning meetings: team sessions where you churn through pending tasks that require collaboration or clarification. For each task, figure out
    - A) what exactly needs to be done
    - B) who is working on it
    - C) what information they need from others
    - Organize the meeting via shared doc where people can add items as they come up

### Make other people work more
It's too easy for someone to task you/commandeer your time at no cost to them... 

> Instead of allowing colleagues to effortlessly lob requests in your direction like hand grenades, leaving you to clean up the mess generated by their productivity-shredding shrapnel, they must now do more work themselves...

Direct them to a Trello board, where they must provide _all_ the info you'll need to complete the task.

### Switch from push to pull
* instead of work being pushed onto a person to queue up next to them, they pull tasks from a queue _when they have the bandwidth._
* a way to balance the good idea fairy (ideas generated much faster than they can be executed)

---

The managerial class didn't know how to handle the autonomy and variety of jobs in this new sector \[of knowledge work\]. Their stopgap response was **pseudo-productivity**, which used visible activity as a proxy for usefulness. 

## _Algorithms to live By_ 
Brian Christian

### The optimal stopping problem
How much time do you dedicate to defining a baseline (looking at houses, circling a parking lot,
looking for a mate) before switching to a mode of "commit immediately to the one that meets your 
criteria"? **Answer: 37%**

- look before you leap
- popularly, the secretary problem

### Explore vs. Exploit
* eat at your favorite restaurant, or a new one; recipes, menu ordering, music listening; reach out 
to a new friend to develop or old friend for familiarity
* in CS, it's embodied in the multi-arm bandit problem: pulling the arms on various slot machines 
and favoring the most promising ones.
* nothing matters as much as **the interval over which we enjoy a thing.** Seize the day because 
you'll die shortly, but seize the lifetime (e.g. start learning an instrument) because you'll live 
longer than you think
* the value of exploration can only go down over time, as the remaining opportunities to savor it 
dwindle
* value of exploitation goes up over time
* Win-Stay, Lose-Shift: choose an arm at random, keep pulling as long as it pays off
* The Gittins Index: originally for drug trials
	- "discounting": valuing the present mor ehighly than the future
	- Deal or No Deal: offering contestants money (a bribe) to _not_ open a briefcase
	- "dynamic allocation index": a guaranteed payout rate which, if offered in lieu of pulling the
	slot machine arm, will make us content to never pull its handle again.
	- it is a pre-calculated matrix of scores per number of wins vs. number of losses (for a single
	"arm"), often discounting the future at 90% the value of the present
* "the grass is always greener" = the unknown has a chance of being better, and exploration has 
value
* Regret Minimization Framework - upper confidence bound algorithm: pick the option (slot machine)
for which the top of the confidence interval is highest
* A/B testing

### Big O Notation
* O(1) constant time - clean for the party
* O(n) linear time - pass around the roast
* O(n^2) quadratic time - each new guest hugs all others
* O(2^n) exponential time - work doubles for each guest
* O(n!) factorial time - hell

* Bubble sort: scan and look for out-of-order pairs
* Insertion sort: pull everything off the shelf and put them back in order
* Mergesort: sort stacks of items separately, then when you merge stacks simply compare the two top 
"cards" (if a deck of cards) and move the smaller to the new stack. This worked in "linearithmic" time. 
* Bucket sort: pre-group into sorted categories w/ no regard for finer, intracategory sorting. Kinda
like partitioning in Spark.

There's a tradeoff between sorting and searching: sometimes searching a messy group is faster. 

Sports: single elimination tournaments, round-robin, ladder tournaments; noise from imperfect
outcomes. Comparison Counting Sort (is sorta like bubble sort). 

Races are better than fights, they are cardinal rather than ordinal outcomes; they're continuous.

### Caching
Consider hardware performance _and_ distance. Random Eviction, FIFO, or LRU. What you've used
recently is a _great_ approximation of what you'll use in the future. Noguchi Filing System:
left-insertion rule (or "top of the pile")

## _Modern Political Warfare: Current Practices and Possible Responses_
Robinson, Helmus, Cohen, Nader, Radin

p. 103
> In a public lecture, Lukyanov described Putin as "not a strategic thinker"—rather, Putin is "prepared for any development" and ready for "immediate reaction." Similarly, Sergei Pugachev, a former aide, noted "Putin is not someone who sets strategic plans; he lives today." Monitoring and tracing Russia's effort to feed crises may therefore be critical for U.S. and NATO efforts to counter Russian political warfare.

## _The Black Swan: The Impact of the Highly Improbable_
Nassim Nicholas Taleb

p. 58
> Popper introduced the mechanism of conjectures and refutations, which works as follows: you formulate a (bold) conjecture and you start looking for the observation that would prove you wrong. This is the alternative to our search for confirmatory instances. If you think the task is easy, you will be disappointed—few humans have a natural ability to do this.

p. 180
> For Hayek, a true forecast is done organically by a system, not by fiat. One single institution, say, the central planner, cannot _aggregate_ knowledge; many important pieces of information will be missing. But society as a whole will be able to integrate into its functioning these multiple pieces of information. Society as a whole thinks outside the box. Hayek attacked socialism and managed economies as a product of what I have called _nerd knowledge_, or _Platonicity_—owing to the growth of scientific knowledge, we overestimate our ability to understand the subtle changes that constitute the world, and what weight needs to be imported to each such change.

## _The Strategy of Conflict_
Thomas C. Schelling

#### Chapter 5: Enforcement, Communication, and Strategic Moves
p. 148
> It is interesting to observe that political democracy itself depends on a game structure in which the communication of evidence is impossible. What is the secret ballot but a device to rob the voter of his power to sell his vote? It is not alone the secrecy, but the _mandatory_ secrecy, that robs him of his power. He not only _may_ vote in secret, but he _must_ if the system is to work. He must be denied any means of proving which way he voted. And what he is robbed of is not just an asset that he might sell; he is stripped of his power to be intimidated. He is made impotent to meet the demands of blackmail. There may be no limit to violence that he can be threatened with if he is truly free to bargain away his vote, since the threatened violence is not carried out anyway if it is frightening enough to persuade him. But when the voter is powerless to prove that he complied with the threat, both he and those who would threaten him know that any punishment would be unrelated to the way he actually voted. And the threat, being useless, goes idle. 


## _Benjamin Franklin_ 
Walter Isaacson

p. 55
> Franklin's small club was composed of enterprising tradesmen and artisans, rather than the social elite who had their own fancier gentlemen's clubs...they discussed issues of the day, debated philosophical topics, devised schemes for self-improvement, and formed a network for the furtherance of their own careers.

p.57
> Franklin went on to catalog the most common conversational sins "which cause dislike," the greatest being "talking overmuch ... which never fails to excite resentment." The only thing amusing about such people, he joked, was watching two of them meet: "The vexation they both feel is visible in their looks and gestures; you shall see them gape and stare and interrupt one another at every turn, and watch with utmost impatience for a cough or pause, when they may crowd a word in edgeways."
> 
> The other sins on his list were, in order: seeming uninterested, speaking too much about your own life, prying for personal secrets ("an unpardonable rudeness"), telling long and pointless stories ("old folks are most subject to this error, which is one chief reason their company is so often shunned"), contradicting or disputing someone directly, ridiculing or railing against things except in small witty doses ("it's like salt, a little of which in some cases gives relish, but if thrown on by handfuls spoils all"), and spreading scandal (though he would later write lighthearted defenses of gossip).

p. 63
> The final Busy-Body that was mainly written by Franklin made fun of treasure seekers who used divining rods and dug up the woods looking for buried pirate loot. "Men otherwise of very good sense have been drawn into this practice through an overweening desire of sudden wealth," he wrote, "while the rational and almost certain methods of acquiring riches by industry and frugality are neglected." The fable, an attack on the get-rich-quick schemes of the time, went on to preach Franklin's favorite theme: slow and steady diligence is the true way to wealth. He ended by quoting what his imaginary friend Agricola said on giving his son a parcel of land: "I assure thee I have found a considerable quantity of gold by digging there; thee mayst do the same. But thee must carefully observe this, Never to dig more than plow deep."

p. 103
> Raising funds [for the Library Company of Philadelphia] was not easy. "So few were the readers at the time in Philadelphia and the majority of us so poor that I was not able with great industry to find more than fifty persons, mostly young tradesmen, willing to pay." In doing so, he learned one of his pragmatic lessons about jealousy and modesty: he found that people were reluctant to support a "proposer of any useful project that might be supposed to raise one's reputation." So he put himself "as much as I could out of sight" and gave credit for the idea to his friends. This method worked so well that "I ever after practiced it on such occasions." People will eventually give you the credit, he noted, if you don't try to claim it at the time. "The present little sacrifice of your vanity will afterwards be amply repaid."

p. 203
> "The man who lives by his labor is at least free."

p. 303
> On the eve of his departure, Franklin wrote two of his British friends to emphasize that America was determined to prevail. "If you flatter yourselves with beating us into submission, you know neither the people nor the country," he told David Hartley. To Joseph Priestly, he provided a bit of math for one of their friends to ponder: "Britain, at the expense of three millions, has killed 150 Yankees this campaign, which is £20,000 a head... During the same time, 60,000 children have been born in America. From these data his mathematical head will easily calculate the time and expense necessary to kill us all."

p. 315
> [Franklin] helped designed, for example, the Great Seal of the new nation, working once again with Jefferson and Adams. Jefferson proposed a scene of the children of Israel being led through the wilderness, and Adams suggested a depiction of Hercules. Franklin's proposal was to have the motto _E Pluribus Unum_ on the front and an ornate scene on the reverse of Pharaoh being engulfed by the Red Sea with the phrase **"Rebellion to Tyrants is obedience to God."** Jefferson then embraced Franklin's plan, and much of it was adopted by the Congress.

p. 318
> ...[Admiral Howe] admitted that he did not have the authority "to negotiate a reunion with America under any other description than as a subject to the crown of Great Britain." Nevertheless, he said, a peace was possible under terms that the Congress had laid out in its Olive Branch Petition to the king a year earlier, which included all of the colonial demands for autonomy yet still preserved some form of union under the Crown. Although he had refrained from being explicit "in my public declaration," he now made clear that the peace he envisioned would be "of mutual interest to both countries." In other words, America would be treated as a separate country within the framework of the empire.
> 
> This was what Franklin had envisioned for years. Yet it was, after July 4, likely too late. Franklin now felt so. Even more fervently, John Adams and others in his radical faction felt that way.

p. 333
> Born in Massachusetts in 1744, [Edward Bancroft] had been tutored as a young man by Silas Deane and then went to work at age 19 on a plantation in Guiana, where he wrote about tropical plants and patented a textile dye made from a native black oak bark. In 1767, at age 23, he moved to London, where he became a physician and stock speculator. 

p. 353
> Franklin was always industrious, and in America he famously believed in also giving the _appearance_ of being industrious. But in France, where the appearance of pleasure was more valued, Franklin knew how to adopt the style. As Claude-Anne Lopez notes, "In colonial America it was sinful to look idle, in France it was vulgar to look busy."

p. 372
> "The game of chess is not merely an idle amusement," he began. "Several very valuable qualities of the mind, useful in the course of human life, are to be acquired or strengthened by it. For life is a kind of chess, in which we have often points to gain and competitors or adversaries to contend with."
> 
> Chess, he said, taught foresight, circumspection, caution, and the importance of not being discouraged. There was also an important etiquette to be practiced: never hurry your opponent, do not try to deceive by pretending you have made a bad move, and never gloat in victory: "Moderate your desire of victory over your adversary, and be pleased with the one over yourself." There were even times when it was prudent to let an opponent retract a bad move: "You may indeed happen to lose the game to your opponent, but you will win what is better, his esteem."

p. 398
> As a master of the relationship between power and diplomacy, Franklin knew that it would be impossible to win at the negotiating table what was unwinnable on the battlefield. He had been able to negotiate an alliance with France only after America had won the Battle of Saratoga in 1777; he would be able to negotiate a suitable peace with Britain only after America and its French allies won an even more decisive victory.

p. 400
> "Such menaces were besides an encouragement with me, remembering the old adage that _they who threaten are afraid._"

p. 422
> His daughter, Sally, sent him newspaper clippings about the formation of a hereditary order of merit...open to distinguished officers of the American army who would pass the title down to their eldest sons. Franklin, replying at the beginning of 1784, ridiculed the concept. **The Chinese were right, he said, to honor the parents of people who earned distinction, for they had some role in it. But honoring a worthy person's descendants, who had nothing to do with achieving the merit, "is not only groundless and absurd but often hurtful to that posterity."** Any form of hereditary aristocracy or nobility was, he declared, "in direct opposition to the solemnly declared sense of their country."

p. 468
> "He that spits against the wind, spits in his own face."

> His final summation of his religious thinking came...in response to questions from the Rev. Ezra Stiles, president of Yale. Franklin began by restating his basic creed: "I believe in one God, Creator of the Universe. That he governs it by his Providence. That he ought to be worshipped. That the most acceptable service we render to him is doing good to his other children." These beliefs were fundamental to all religions; anything else was mere embellishment.

p. 491
> Compromisers may not make great heroes, but they do make great democracies.

## _Democracy in America_ 
Alexis de Tocqueville

p. 61
> Liberty regards religion as its companion in all its battles and its triumphs, as the cradle of its infancy and the divine source of its claims. It considers religion as the safeguard of morality, and morality as the best security of law and the surest pledge of the duration of freedom. 

p. 103
> Laws are always unstable unless they are founded upon the customs of a nation: customs are the only durable and resisting power in a people. 

p. 124
> The greatest advantage of religion is to inspire diametrically contrary principles. There is no religion that does not place the object of man's desires above and beyond the treasures of earth and that does not naturally raise his soul to regions far above those of the senses. Nor is there any which does not impose on man some duties towards his kind and thus draw him at times from contemplation of himself. This is found in the most false and dangerous religions. 

p. 125
> Mohammed professed to derive from Heaven, and has inserted in the Koran, not only religious doctrines, but political maxims, civil and criminal laws, and theories of science. The Gospel, on the contrary, speaks only of the general relations of men to God and to each other, beyond which it inculcates and imposes no point of faith. This alone, besides a thousand other reasons, would suffice to prove that the former of these religions will never long predominate in a cultivated and democratic age, while the latter is destined to retain its sway at these as at all other periods. 

p. 217-18
> Our forefathers had conceived a strange opinion on the subject of marriage; as they had noticed that the small number of love matches which occurred in their time almost always turned out badly, they resolutely inferred that it was dangerous to listen to the dictates of the heart on the subject. Accident appeared to them a better guide than choice. 
> 
> Yet it was not difficult to perceive that the examples that they witnessed in fact proved nothing at all. For, in the first place, if democratic nations leave a woman at liberty to choose her husband, they take care to give her mind sufficient knowledge and her will sufficient strength to make so important a choice, whereas the young women who among aristocratic nations furtively elope from the authority of their parents to throw themselves of their own accord into the arms of men whom they have had neither time to know nor ability to judge of are totally without those securities. 
